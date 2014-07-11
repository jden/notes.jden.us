---
---
# projects

just a few projects which are currently bouncing around in my head

## lurker purgatory

how do you hellban people in reverse to mitigate stalking in public fora?

a way to protect open and "signon-less" online community spaces from
stalkers and other unwanted, negative community behavior.
based on ideas of persistent cookies and strong fingerprinting.
certain actions serve to "build trust" in a user session,
which enable fuller participation in the network.
users have fine-grain control over their privacy settings and can
two-way mute other people, even if the other people aren't visibly participating. analogy of a bar where lighting and other atmospheric
conditions affect the social engagement which happens there. should
welcome newcomers and protect actual community, rather than holding
to an abstract ideal of openness or anonymity.


## jsig

precise and concise javasccript type annotation. support better human usability of modular source code. describe interfaces easily and uniformly. work is also being done on a parser and a grammar to support tooling such as verification, type inference, etc.


## rel

linked data message protocol. open, decentralized. useful for passing messages about. built on top of the web (http, json). useful for building things like notifications and for communicating between services. decentralized like email, fallback like mozilla persona.


## indiefinger

- webfinger (rfc 7033) compatible on the consumer end
- proxy to webfinger if target server exists
- since it doesnt, also be clever about scraping linked data from other sources
    - html/http rel links
    - site-specific user profiles (twitter, etc)
- run it as a service, also as a module which can be run decentralized eg via cli


## indiegist

- super simple micropublishing for notes and comments and pastebin stuff
- backed by git
- hosted on your own domain
- support webmention to reply to other content


## simple stats

- a no-brain replacement for googleanalytics that gives you pretty charts and some basic stuff for when you really just want a hitcounter but don't want to give google all of your data
- also something suitable for service tracking


## mirror open data

- one-click clone socrata data catalog into a new or existing ckan instance
- archive open data sets to eg internet archive on a regular basis (possibly to something better suited for changing data with better version support, eg dat)