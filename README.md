# Flink Deep Dive

Resources I used to understand Flink source code while working on UROP. Hope this will be useful for others who also wish to hack on Flink (it's very difficult and takes a long time to understand codebase)

But Flink is super optimized and many things you learn, you can apply to your own future systems if you wanna be a systems programmer/researcher

## TODOs

Make technical ppt for modifications for CoD

1. Why use checkpointing mechanism?
   1. Natural sync, ensures consistency and clear epoch partition
2. Serialization could be improved

## Stuff

1. Custom Serialization - native byte serialization, super fast comparison
2. Manual memory management, you can have really good performance with Java if you only use 80% and prevent stop-the-world

## Credits

Scattered all over the internet.
Mao Yancan (PhD Mentor)
