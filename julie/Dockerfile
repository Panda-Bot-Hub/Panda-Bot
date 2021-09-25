FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Panda-Bot-Hub/Panda-Bot /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit 
CMD ["node", "bot.js"]
