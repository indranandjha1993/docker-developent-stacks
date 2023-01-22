FROM ruby:latest

COPY src/ /ruby

WORKDIR /ruby

RUN bundle install

CMD ["rails", "server", "-b", "0.0.0.0"]
