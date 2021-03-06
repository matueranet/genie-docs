Genie
==============

This repository is a collection of documentation for all Genie related products. The
different codebases are still being written, this documentation will now only
contain the combined roadmap.

For regular updates on the development process [follow us on Twitter](https://www.twitter.com/matueranet).

# Genie related repositories

## genie-ai

An npm module that allows someone to easily create an application that listens for speech input (stt).
and responds via speech to text (tts). Features offline hotword/wake word detection and supports
multiple tts engines, both offline and online.

**Development on this project has gotten a lower priority, it has turned out to be very difficult to develop a reliable and fast voice recognition service, focus is now more on genie-router. Once that project is stable, voice will get more priority.**

[repository](https://github.com/matueranet/genie-ai)

## genie-point

A node application that can run on light-weight hardware such as a Rasperry Pi. Implements
the genie-ai module and offers several different interfaces (socket, http, etc) to access
the data.

Will feature automatic detection of devices running genie-point in the same network.

[repository](https://github.com/matueranet/genie-point)

## genie-router

A piece of software which will offer a uniform interface into one or more devices running
genie-point. The devices can be queried or sent commands via the same interface.

Besides genie-point it will support several other interfaces. It can be used both as a module
or as a stand-alone application.

[repository](https://github.com/matueranet/genie-point)

# Roadmap

See [roadmap.md](https://github.com/matueranet/genie-docs/blob/master/ROADMAP.md) for details on
the roadmap.
