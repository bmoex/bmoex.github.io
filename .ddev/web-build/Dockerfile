# install jekyll for ddev usage
RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y -o Dpkg::Options::="--force-confnew" --no-install-recommends --no-install-suggests autoconf
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y ruby-full build-essential zlib1g-dev

USER $username
RUN echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc \
    && echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc \
    && echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc \
    && source ~/.bashrc

#RUN GEM_HOME="$HOME/gems" gem install jekyll bundler
USER root
