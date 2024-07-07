FROM alpine

RUN echo hello xxx >> /tmp/xxx
RUN echo hello yyy >> /tmp/yyy
RUN ["sh", "-c", "echo hello zzz >> /tmp/zzz"]

CMD ["echo", "hello docker"]
CMD echo hello world
CMD cat /tmp/xxx /tmp/yyy
CMD cat /tmp/zzz
