FROM btwiuse/ufo AS ufo

FROM btwiuse/arch:node

COPY --from=ufo /usr/bin/ufo /usr/bin/ufo

RUN sudo npm i -g bun
