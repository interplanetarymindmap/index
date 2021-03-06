_This is Xavi's sketch file for ideas, issues, readmes... anything that is not fully developed yet_\

# Research

# Mappers and packers
Once I realized that we could treat each mind-map node as a [literal definition](https://github.com/interplanetarymindmap/mind-map/issues/2), it was pretty much impossible to me to concieve an alternative usage.

With this in mind the data structure evolved trying to protect this construction.

Dani rapidly raised his hand and argued that if we benefit the mentioned construction, we may be biasing the design towards people that think in a very specific way, therefore going against [our main goal](https://github.com/interplanetarymindmap/mind-map#mind-map-1):
>The idea of a mind-map, a tool that allows organizing information in the way that your brain works and not in a simplified way restricted by a user interface or a data structure.

I argued that a `semantic triple` is a subset of a `definition`. So, with the `definition` construction we can always represent a triplet, while the opposite makes the `definition` prone to the corruption of its integrity.

A paralel argument was that if someone is not interested on defining concepts, and is just looking for an `snapshot` of the state of certain information, then it does not matter that much how the data is represented, because it does not transcend the `snapshot` itself.
The `definition` instead, cares deeply, because the corruption of a `definition` will effect all the `definitions` that that used the corrupted one.

## Mappers and packers

Last week [Ivan](https://github.com/divan), introduced to me to the concept of _mappers and packers_, descrived in [Programmer's Stone](http://www.programmersstone.com/).

I believe it to be a mandatory read for anyone working in this project.
A summary from the same essay:
> Packing was characterised as a socially conditioned habit of accreting "knowledge packets" that specify "appropriate action", and not examining or reconfiguring the relationships between the knowledge packets. The strategy degenerates into kludging reality to fit the known packets and blaming luck when things go wrong. Mapping on the other hand, involves putting investment into building an internal object model of the world as it is perceived and getting leverage by identifying deep structure. Mapping can be developed by learning techniques that help the exploration of conceptual spaces and help one recognise what it is that one is actually seeing happening in front of one's own eyes, by recognising the deep structure patterns in the goings on. Mappers can respond flexibly and are the only people in a position to propose new approaches. They can learn vastly more quickly than packers, and unless they are seeing deep structure, they are seeing as yet unsolved mysteries. The experience of mappers and packers may be quite different, in exactly the same circumstances.

I believe that the description of `mappers` and `packers` mindsets matches perfectly the constructions of `definitions` and `snapshots` descrived above.

It also makes ovious that a mind-map tool is for mappers. A packer can still use the tool, of course, but it wont make use of its potential.

# No concensus
- We want to enhance the mind. And its subjective view.
- Personal ontology
- Our tools don't serve a platform but a mind.
- Concensus is a layer on top of the mind subjective view.

# Bi-directional links

# Relationship dimensions

# Documentation praxis manifesto
- Documentation should be implicit when possible (ex: function with a good descriptive name), otherwise
    - Documention should be derived from the implementation automatically
- Documentation needs to be acessible. Is not ok for a documentation to exists if is hard to reach
- Avoid links that can be broken easly.
- No broken documentation. No todos, no WIP. A documentation entry should be be cohesive with itself. While a section with WIP may be necessary
- Documention should be developed in paralel of an implementation. (Ex: Do not accept a PR without its corresponding documentation)
- KISS: Can you say the same with less words. Can you use easier words?
- https://github.com/RichardLitt/standard-readme

# Encapsulation
- The smaller the encapsulation, the more reasuable
- Context

# How to create links

### Node
We are working towards eliminating this word from our dictionary because it keeps generating confusion. There are a lot of types of nodes, they almost represent the same thing, but they don't.

### Node cluster [OUTDATED]
One of the [original specs](##-original-specs) was:
> It needs to work on a global domain. This means that two different mindmaps pointing to the same concept should converge if put together

We call this convergence a `node cluster`. In other words is the set of nodes that are pointing to the same `CID`.

### Others

### People to interview
Programers stone
RDF
Juan Benet

## Terminology
We started talking about `nodes`, `origins`, relation `types` and `targets`.

## Identities vs entities

My understanding of identity is everything that conforms a particular entity. Applied to a human, is the acumulation of all our past experiences. What makes you who you are. It the digital domain those are the digital traces that define you.

### Proofs
I've work extensively with the idea of decentalized identites. First on Uumm, and currently with Vocdoni.

There are plenty of projects that are trying to model how a decentralized identitty opperates. Mostly batteling on how to circumvent the limitations of blockchains and how to give strong privacy guarantees.

What they all have in common is that they want to be able to prove a claim over the state of an entitiy.

### True identity
If we take the previous definition, and identity is much more that what you can prove to others. And in this sense, someone's mind-map would be a much better representation of identity than the few provable claims used on a KYC process.

Indeed they have very different purposes, but a claim on a blockcain or `relation` on our `mind-map` are exactly the same thing. We're just defining idenitites from a much lower level.

We need to think how we can eventually proof, or show to others or view on a specific subject without showing the full tree that conforms a definition. This goes hand in hand with the accessibility layer that we haven't tackled yet, but I hoping to write about it soon enough.

## Mappers and packers extra links
https://www.reddit.com/r/NotarySojac/comments/zavp9/welcome_to_reciprocality/


## Decentralized OS
Google's Chrome OS, has moved very fast in recent years, to the point that my main machine is a Google Pixelbook. It works great and I can run Chrome OS, Android and Linux within a unified user interface thanks to its [container support](https://chromium.googlesource.com/chromiumos/docs/+/master/containers_and_vms.md)

Chrome OS is the closed-source version of Chromium OS.


Would it make sense to start a distribution of Chromium OS focused on natively enabling decentralized technologies for the end user?

- IPFS support
- Key managament
- ENS resolution

https://dappnode.io/