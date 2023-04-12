FROM quay.io/pepesir/bosco-md:beta
RUN git clone https://github.com/TOXIC-KRIZ/BOSCO-MD /root/BOSCO-MD
WORKDIR /root/BOSCO-MD
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"] 


