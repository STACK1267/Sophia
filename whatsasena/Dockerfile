FROM fusuf/whatsasena:latest

RUN git clone https: https://github.com/STACK1267/Sophia.git/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
