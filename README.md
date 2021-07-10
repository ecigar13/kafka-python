# kafka

## What I learned
- Very complex to start (Apache tutorial is wrong) - that's why there're companies like Confluent, Cloudurable offering manager service
- I can make tweaks to the streams to filter, format messages before they're read.
- After that, things get easier.

## Pros
- Easy to prototype (if I can get past the wrong tutorial)
- Producers, consumers, transformers are modular
- Scalable (but only up)

## Cons
- Tough to start from scratch. Java is verbose.
- No native UI to manage.
- Too much work for a small or one-man businesses.

## Important commands
```mvn compile exec:java -Dexec.mainClass="myapps.WordCount"```