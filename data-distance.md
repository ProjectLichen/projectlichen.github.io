# Data Distance

> **How far must data travel before meaning can be extracted and useful action becomes possible?**

Data Distance is a Project Lichen inquiry into the movement of information.

It began with a relatively simple observation: modern computing systems frequently move enormous quantities of data before deciding what that data means.

A sensor may generate information locally.

That information may cross a device boundary, network interface, protocol stack, local network, internet connection, data centre and several software layers before useful interpretation occurs.

But physical distance is only one kind of distance.

Project Lichen uses **Data Distance** to explore the physical, network, computational, protocol, architectural and representational boundaries that information crosses before meaning is extracted and useful action becomes possible.

The central question is not necessarily:

> **How can we move data faster?**

It may instead be:

> **How far did the data need to travel in the first place?**

---

## Distance Is More Than Geography

The word *distance* initially suggests geography.

A sensor in one place sends information to a computer somewhere else.

That physical journey matters, but it is only part of the story.

Two pieces of information may be physically only centimetres apart while being computationally far apart because of the systems through which they must communicate.

Conversely, information may travel geographically across a considerable distance through a relatively simple architectural path.

Data Distance may therefore include:

- **physical distance** — how far information moves geographically
- **network distance** — the network boundaries and links crossed
- **protocol distance** — the translations and protocol layers involved
- **computational distance** — how much processing occurs before meaning emerges
- **architectural distance** — the systems and abstractions information must traverse
- **representational distance** — how far raw measurements are from useful meaning

Data Distance is therefore not simply a measurement in metres, milliseconds or network hops.

It is an attempt to make the journey from:

**observation → information → meaning → action**

visible.

---

## Extract Meaning Earlier

Many modern systems follow a pattern resembling:

**sensor → raw data → network → remote infrastructure → storage → computation → meaning**

But another possibility is:

**sensor → local interpretation → meaning → useful information travels**

The second architecture does not necessarily eliminate networks, data centres or centralized computation.

It asks whether all of the raw information needs to travel there.

If useful meaning can be extracted closer to where information originates, less data may need to move.

That may affect:

- energy consumption
- bandwidth
- latency
- infrastructure requirements
- storage requirements
- privacy
- resilience
- dependency

This is related to edge computing, but Data Distance asks a somewhat broader question.

> **Where is the earliest useful place at which meaning can emerge?**

Sometimes that may be a sensor.

Sometimes a local device.

Sometimes a nearby computer.

Sometimes a regional system.

And sometimes the useful meaning can only emerge after information from many places has been combined within substantial shared infrastructure.

The appropriate answer depends upon the problem.

---

## Reduction Is Not Necessarily Loss

Moving less data does not necessarily mean knowing less.

Raw measurements may contain enormous amounts of repetition or information irrelevant to a particular decision.

A system might therefore transform:

**many observations → useful pattern**

or:

**continuous measurements → meaningful change**

or:

**raw data → local interpretation → exception**

Instead of transmitting everything continuously, a system may communicate when something important changes.

The challenge is deciding what can safely be reduced.

Premature interpretation can discard information that later proves valuable.

For that reason, Data Distance is not simply an argument for aggressive data reduction.

It asks us to examine the relationship between:

**what is observed**

**what is retained**

**what is transmitted**

**what is interpreted**

and

**what decisions remain possible afterward**

---

## Follow the Friction

One practical way of discovering Data Distance is surprisingly simple:

> **Follow the friction.**

When a digital process is unexpectedly slow, expensive, energy-intensive or dependent upon substantial infrastructure, trace the path.

Where does the information originate?

Where does it go?

Which boundaries does it cross?

Where is it copied?

Where is it transformed?

Where is it stored?

Where is meaning finally extracted?

And which parts of that journey were actually necessary?

A performance problem may appear to belong to an application while its real cause exists somewhere else in the architectural path.

A networking problem may actually be a virtualization problem.

A storage problem may originate in the amount of raw information retained before aggregation.

An energy problem may partly be a data-movement problem.

Data Distance therefore provides not only a conceptual lens but a practical investigative method:

> **Follow the information. Follow the friction.**

---

## Local and Distributed Capability

Centralized computing provides extraordinary capabilities.

Large shared systems can combine information, computational resources and specialized hardware at scales that would be impractical to reproduce locally.

Distributed systems offer different possibilities.

Some interpretation may occur close to sensors.

Local computers may perform useful inference without requiring every observation to leave the site.

Network devices may aggregate or interpret information while it is already moving.

Several modest machines may cooperate.

Information may be summarized before travelling farther.

The useful question is therefore not:

> **Centralized or distributed?**

It is:

> **Which information needs to travel, how far does it need to travel, and which computation can usefully occur before it does?**

This makes Data Distance partly an inquiry into **where capability resides**.

---

## Data Distance and Living Systems

Living systems provide an interesting comparison.

Biological systems are highly distributed.

Cells sense and respond locally.

Plants respond to light, water, gravity, temperature, damage and chemical signals through processes distributed throughout the organism.

Ecological systems emerge from enormous numbers of interactions occurring without a single central processor receiving every raw observation.

This does not mean engineered systems should simply imitate biology.

Nor does it mean biological systems have no long-distance communication or coordination.

Instead, they raise an interesting question:

> **What might engineered systems learn from systems in which observation, interpretation and response frequently occur close together?**

Technology may also allow us to observe these biological processes differently.

A plant sensor, for example, might continuously transmit raw movement data elsewhere for interpretation.

Another system might distinguish locally between short movement caused by wind, persistent bending, circadian movement or some other meaningful change, transmitting only what requires further attention.

The plant and the computer then become part of the same Data Distance experiment.

---

## Measuring Data Distance

Data Distance does not yet have a single measurement.

That may be useful.

Reducing the idea immediately to one number could conceal the relationships we are trying to understand.

Instead, an experiment might record several characteristics:

**Where did the data originate?**

**How much raw data was produced?**

**Which physical distance did it travel?**

**Which network boundaries did it cross?**

**Which protocol or architectural boundaries did it cross?**

**How much information was retained?**

**Where was interpretation performed?**

**How much information remained after interpretation?**

**How much energy and infrastructure did the journey require?**

**How quickly could useful action occur?**

Different architectures can then be compared experimentally.

The objective need not be to declare one architecture universally superior.

It is to make otherwise invisible journeys observable.

---

## Beyond Data

Data Distance has begun raising related questions.

Food travels before reaching need.

Materials travel through extraction, manufacture, use, reuse and disposal.

Energy moves through generation, transmission, storage and conversion.

Money and financial representations may pass through layers increasingly distant from the physical capabilities they represent.

Knowledge may travel through institutions and abstractions before reaching people able to act upon it.

These are not necessarily forms of Data Distance.

But they suggest a broader Project Lichen question:

> **How much distance exists between a need and the capability capable of meeting it?**

The emerging idea of **Material Distance** may provide one way of exploring the physical counterpart to Data Distance.

Project Lichen will keep these ideas distinct enough that useful differences are not lost merely because the analogy is attractive.

---

## Data Distance and E-Cropolis

[E-Cropolis](e-cropolis.md) provides a particularly interesting environment in which Data Distance may eventually be explored.

A simulated city produces enormous amounts of state.

Not every observer needs every piece of that state.

A building may have information about occupants, water, food, energy, soil, materials and biological activity.

A neighborhood may need aggregated information.

A city-wide system may need something different again.

An artificial-intelligence observer may require a meaningful representation of the simulation rather than every internal variable generated during every simulation tick.

This raises a practical architectural question:

> **How much raw simulation state must travel before useful meaning can be extracted?**

E-Cropolis can therefore investigate Data Distance not merely as something represented inside the simulated city, but as a property of the software architecture running the experiment itself.

---

## Experiments and Observations

Data Distance is intended to develop through practical experiments as well as conceptual inquiry.

Areas being explored include:

- local artificial-intelligence models
- distributed computers and mobile devices
- computation near sensors
- edge computing
- computation within network paths
- low-energy computing architectures
- data aggregation before storage
- plant sensing and local interpretation
- communication between local AI agents
- architectural and virtualization boundaries
- E-Cropolis simulation interfaces

Individual experiments may be small.

A network transfer.

A sensor.

A local language model.

A single-board computer.

A comparison between two architectural paths.

The important thing is that they can produce observations.

Over time those observations may reveal which parts of Data Distance are useful, which require refinement and which turn out not to matter.

---

## An Experimental Inquiry

Data Distance is not presented as a finished theory.

Nor does it claim that computation should always occur locally.

Some information becomes more useful when combined across large distances.

Some problems require substantial centralized computation.

Shared infrastructure can provide capabilities that local systems cannot reasonably reproduce.

Redundancy and distributed systems themselves can sometimes increase complexity and resource use.

The purpose of Data Distance is therefore not to minimize distance at all costs.

It is to make distance visible enough that it can be questioned.

We can ask:

**Where did the data originate?**

**What journey did it take?**

**Which boundaries did it cross?**

**Where was meaning extracted?**

**Could useful interpretation have occurred earlier?**

**What did moving the data require?**

**What capability existed locally?**

**What capability existed remotely?**

**What information was discarded?**

**What information needed to be preserved?**

**What would happen if the connection between them disappeared?**

And ultimately:

> **Did the distance enlarge capability—or merely become an unnoticed requirement?**

---

## A Working Method

For now, Data Distance can be approached with a simple method:

> **Don't begin by assuming where computation belongs.  
> Follow the information.  
> Follow the friction.  
> Observe where meaning actually emerges.**

That method connects Data Distance with the wider Project Lichen approach:

> **Observe carefully.  
> Learn continually.  
> Share generously.**

And with the question that continues to connect the project:

> **What capabilities remain?**

---

**Data Distance**  
*A Project Lichen living inquiry into the movement of information*

← [Technology](technology.md) | [Home](README.md)
