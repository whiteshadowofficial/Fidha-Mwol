FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Mr-WHITE-SHADOW/Fidha-Mwol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Hypersir/media

CMD ["node", "bot.js"]
