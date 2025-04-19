## hololinked

Hi there 👋

`hololinked` solves the following requirement in python:
- You want to remotely control, monitor and retrieve data from one or many measurement devices and hardware
- You want to use known web technologies like HTTP protocol and JSON data format but have the flexibility to go beyond them when necessary. For example - you can use message pack or pickle for streaming complex n-D numpy arrays frame by frame efficiently at high speed.
- Object Oriented coding style and zero initial setup - a python script can expose your device
- If you are really advanced in your coding skills, you are looking for a well defined (web-)API to interact with your device 
- If you are only a beginner, you really want to build your knowledge systematically in an easy to understand format without worrying about the underlying complexity. You can start with simple devices talking over interprocess communication and may be write a PyQt or matplotlib script to visualize the data retrieved. You can think about building a web interface or using "APIs" later.
- Preoptimization for performance and security (as far as what python can achieve)
- Interoperability with other systems and languages through an upcoming web standard called [Web of Things](https://www.w3.org/WoT/) (WoT)
- Fully open source
- High level implementation where the underlying logic can be easily inspected and modified

Only the security is not yet implemented yet (except SSL and rejecting unknown clients by IP which are supported) and as far as protocols are concerned, HTTP and ZMQ is supported, but improvements are on the roadmap and should be out in the very near future. 

Anyway, for the above stated requirements, `hololinked` is the right choice. Dont put together a myriad of python tools and protocols to build your own server just because you can do that in python. Broad minded choices have already been taken for you, that is, if you are willing to stick to object oriented paradigm.

`pip install hololinked`
`conda install -c conda-forge hololinked`

<a id="all-links"></a>

Also see: 

[Documentation](https://hololinked.readthedocs.io/en/latest/)

[Live Demo](https://control-panel.hololinked.dev/#https://examples.hololinked.dev/simulations/oscilloscope/resources/wot-td)

[Examples](https://github.com/hololinked-dev/examples)

[Contribution Guidelines](../CONTRIBUTING.md) if you wish to join, I am actively looking for contributors  

[Code of Conduct](../CODE_OF_CONDUCT.md)

[Project Planning](https://github.com/orgs/hololinked-dev/projects)

[Donating](https://github.com/sponsors/VigneshVSV)

[Website](https://hololinked.dev)

<a id="monthly-meetings"></a>

[![Discord](https://img.shields.io/discord/1265289049783140464?label=Discord%20Members&logo=discord)](https://discord.com/invite/kEz87zqQXh)

Monthly meetings are held on the first Wednesday of every month at 1600hrs until 1700hrs German time (CET). In these meetings, I will be discussing the project, its future, technical ideas, issue planning-assignment-review etc.

Any other discussions or Q&A, issue reviews or discussions happen on following wednesdays every week at 1700hrs German time (CET) and 0900hrs German time alternatively for approx 1hr duration. 

Feel free to join the meetings, no question is a dumb question. There is no any real participation from community as of time being and I am trying to kick-start it. Link to meeting in discord group or send email to admin@hololinked.dev.

<a target="_blank" href="https://calendar.google.com/calendar/embed?src=3d5d7524047fb738b474d09d67c4456646160a770c0d92e5c493297777a85be6%40group.calendar.google.com&ctz=Europe%2FBerlin"><img border="0" src="https://calendar.google.com/calendar/images/ext/gc_button1_en-GB.gif" alt="Google Calendar"></a>

[Calendar ICS](https://calendar.google.com/calendar/ical/3d5d7524047fb738b474d09d67c4456646160a770c0d92e5c493297777a85be6%40group.calendar.google.com/public/basic.ics)

If you would like to added to organisation, please contribute to some issues or join the weekly discussions. I will be happy to add you to the organisation. If you are already contributing and would like to be added, just write to me in discord or by email. 

Discussions & Q&A can also be opened here: 
- [General Discussions about the entire project](https://github.com/orgs/hololinked-dev/discussions)
- Each repository have their own discussions section as well which is more specific 
- Discord

<a id="good-first-issues"></a>

For good first issues, visit repository wise:
- [hololinked](https://github.com/hololinked-dev/hololinked/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22)
- [thing control panel](https://github.com/hololinked-dev/thing-control-panel/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22)
- [website](https://github.com/hololinked-dev/website/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22)
- [examples](https://github.com/hololinked-dev/examples/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22)
- [documentation](https://github.com/hololinked-dev/docs-v2/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22)

<a id="gitlab-section"></a>

[Gitlab Repositories](https://gitlab.com/hololinked)