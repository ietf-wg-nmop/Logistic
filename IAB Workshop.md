IAB workshop on the Next Era of Network Management Operations  (NEMOps)

# Introduction

The IAB organized a workshop in June 2002 to establish a
dialog between network operators and protocol developers, and to guide
IETF when working on network management protocols. The
outcome of that workshop was documented in the "IAB Network Management
Workshop" [RFC3535] which identified 14 recommendations for
consideration in future network management protocol designs.

Those requirements were instrumental for developing first the NETCONF
protocol (in the NETCONF Working Group) [RFC6241], the associated YANG
data modeling language (in the NETMOD Working Group) [RFC7950], 
RESTCONF [RFC8040], and most recently CORECONF.

This new workshop aims at discussing multiple topics, including
a historical recap of the results from the last workshop, what the
current state-of-the-art and deployment look like today, what are the recommendations that were not followed, and what are
the hurdles that were encountered when operationalizing the recommendations.

# Review of the 2002 workshop outcomes

This IAB workshop will look at whether the recommendations documented by the previous 2002 workshop were met,
and (more importantly) will gather new input on what new issues network
operators and network management implementers are facing.  This
workshop ambitions to lay a new directional foundation for the continued
future of network management protocols.  Recommendations that come out
of this effort should be helpful to the global industry, including the IETF, the IRTF, as well as
implementers, operational groups, and other entities.

# Current state-of-the-art

Taking into account the [RFC3535] recommendations, what do
implementations and deployments look like today? If there are any issues
experienced during implementation, what are they?  Do operators deploy
designs that are based upon IETF network management standards? If not, do
operators think that further specifications that would document key features or
requirements should be worked on and published (possibly by the IETF)? 
Are there any alternate solutions that better fit the operators' needs than those that exizt today (including those that rely upon IETF standards)? Etc.

# Laying a path for the future of Network Management

Network topologies have become significantly more complex since the
2002 IAB workshop, as have the router and host technologies. 
Assuming this trend will only be continuing, this
workshop intends to explore what previous recommendations still stand
as unfulfilled, whether they remain relevant, and what new
recommendations exist in the changing landscape. For example,
configuration management and automation techniques have become increasingly
important to enable large scale rollouts. What protocols, libraries
and tools are needed to enable network management at scale?  What
balance of open source vs. proprietary networks are deployed today, and
which architectures are expected to work continuing forward?

# Out of scope topics

This workshop intends to focus on managing networks within the control
plane (and its effect on the data plane), but management of content
within the data plane is explicitly out of scope.  Specifically, a
workshop dedicated to management techniques related to encrypted
networks has already been held [RFC9490] and these topics are therefore out of
scope for this workshop.

# Outreach and Timeline

In 2002, many network operators attended IETF meetings and
participated in network management protocol discussions. Direct
participation of network operators have since dwindled, with many
operators focusing on conferences that are more central to their
needs -- these include RIPE, NANOG, AutoConn, etc.

Under this effort we expect to stimulate an outreach effort to
attract opinions and interest by visiting these other venues. This workshop
will be followed by a final virtual workshop that will be
tentatively organized in December 2024.  Until the final workshop draws
close, the mailing list will be used for interim participation/BoFs at
other conferences, general announcements and any related discussions.

