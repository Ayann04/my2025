RUN wget -q -O /tmp/chrome.deb https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb && \
    apt-get update && apt-get install -y /tmp/chrome.deb || apt-get -f install -y && \
    rm -rf /var/lib/apt/lists/* /tmp/chrome.deb
