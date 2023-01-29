---
layout: page
title: Services
show_sidebar: false
---

# Collecting, managing and processing stream data

IoT and 5G technologies make it feasible to acquire data at scale, but
there are several steps before data can be used for extracting
actionable information and insights through analytics and AI:
Data needs to be indexed so that the data that is relevant for
different analyses can be located, organized in a way that is amenable
for scalable processing, integrated with other streaming and static
data sources, and annotated with the lineage and provenace metadata
needed to estimate trust and to ensure regulatory compliance.


# Scalable advanced analytics and AI

Extracting statistical quantities from streaming data is covered by
practically every Big Data stack. However, more advanced analytics has
not been natively ported to scalable infrastructures but scalability
is limited to arbitrarily partitioning the signal, which affects the
results in subtle but often significant ways. From conventional
digital signal processing algorithms to state-of-the-art AI and Deep
Learning architectures, treating a stream of data as a continuous,
evolving entity is a completely different approach than partitioning
it into a series of processing blocks.


# Environmental footprint

Overlapping partitioning, sliding windows, and similar techniques can
very well be used (and are used) to alleviate the problem and produce
identical or practically-identical results to what the original
algorithm would tield if it could be applied to the complete signal.
However these techniques operate on the assumption that computational
resources are unlimited and that spending computational resouirces is
far more efficient than spending development effort. This assumption
needs to be critically revisited in the face of the urgent and
pressing need to reduce CO2 emissions. Computing is a major
contributor of greenhouse gas emissions, with Deep Learning and
analytics claiming an onersized share of the overall computing cycles
spent. Improving the quality of our scaling methods and the quality of
the implementations of our core analytics algorithms is no longer a
luxury but an absolute necessity.


# Low code

However this does not necessarily mean that every organization that
analyses data needs to spend the human resources need to implement
extremely lean code or that in-house analytics needs to be completely
replaced by off-the-shelf software: The former is not viable and the
latter is too restrictive. We advocate a low-code approach where
Python or similar scripts orchestrate carefully-crafted
general-purpose libraries of scalable digital signal processing and
deep stream analytics, to achieve task-specific goals. Consider, for
example, how the NumPy library offers a semaless Python interface over
extremely streamlined C implementations of array manipulation
operators. We offer a similar experience (and efficiency and
performance) for distributed signal and stream processing.


# Cloud Native

Naturaly, such a signal and stream processing backend can only be
useful if it is natively build for modern Cloud-based computing
environments.

