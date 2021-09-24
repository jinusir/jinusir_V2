FROM fusuf/whatsasena:latest

RUN git clone https://github.com/shadow-sir_v1/shadow-sir_v1 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
