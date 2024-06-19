FROM ruby

WORKDIR /api

COPY ./ /api

RUN bundle install

EXPOSE 3000

ENTRYPOINT ["sh", "entrypoint.sh"]