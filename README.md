# Flow Interoperability (FLOIP) "Flow Definitions": An Open Specification for Flows

A container and data format for describing the *content and logic of digital interactions*, using the Flow Data paradigm. It provides for the open publication, exchange, and analysis of Flow-like content across supporting platforms. 

Flows represent a collection of actions ("Blocks") and the decision-making logic that links Blocks together into a flowchart-like description of an interactive mobile service, business process, or anything else that can be modelled as programmatic flow-chart.

<table>
  <tr>
    <td>Authors</td>
    <td>Mark Boots (VOTO Mobile)<br>
Peter Lubell-Doughtie (Ona)<br>
Eduardo Jezierski (InSTEDD)<br>
Gustavo Giráldez (InSTEDD)<br>
Evan Wheeler (UNICEF)
  </tr>
  <tr>
    <td>Media Type</td>
    <td>TODO: once registered:
application/vnd.org.flowinterop.flows+json</td>
  </tr>
  <tr>
    <td>Version</td>
    <td>1.0.0-rc.1</td>
  </tr>
  <tr>
    <td>Last updated</td>
    <td>2017-09-22</td>
  </tr>
  <tr>
    <td>Created</td>
    <td>2016-09-10</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
</table>

## Introduction

The purpose of the project is to enable useful interoperability between Flow-based platforms, and to incentivize the joining of future software tools into an interoperable ecosystem.  We will accomplish this through a set of open specifications, and a set of open-source toolsets that reduce barriers to adoption.  The initial focus is on tools for mobile/web engagement, although the most basic layer of the specification is general and can represent non-mobile business logic.

### What are Flows?

Flows are a modern paradign for describing the logic of digital information systems that interact with individuals, often for the purpose of (a) collecting data or (b) providing information through interactive requests.  Some common examples of this are in mobile services using voice-based or SMS-based conversations over basic mobile phones. Flows follow the "flowchart" paradigm, consisting of actions (nodes) and connections between actions, which can incorporate decision-making logic.

### Who is working on this?

This is an initial collaboration between makers of Flow-like platforms and supporting tools: Nyaruka, InSTEDD, Ona, and VOTO Mobile.  UNICEF and USAID are providing guidance and input.  The project received initial funding from USAID. We intend that this project will outlast USAID funding and grow beyond the initial set of collaborating organisations. For more information on how to contribute, see [Project Charter and Governance Rules](charter.md).

## Specification - Table of Contents

0. [Language](#language)
2. Fundamentals
    1. [Glossary and Definitions](fundamentals/glossary.md)
    2. [Flow Fundamentals](fundamentals/flows.md)
        3. [Containers](fundamentals/flows.md#containers)
        3. [Flows](fundamentals/flows.md#flows)
        3. [Blocks](fundamentals/flows.md#blocks)
    5. [Expressions](fundamentals/expressions.md)
    6. Layers in the Specification
    7. Layer Documentation
        1. [Layer 1: Core](layers/layer1/blocks.md)
        2. [Layer 2: Console IO](layers/layer2/blocks.md)
        3. [Layer 3: Mobile Primitives](layers/layer3/blocks.md)
        4. [Layer 4: Smart Devices](layers/layer4/blocks.md)

## Language

The key words MUST, MUST NOT, REQUIRED, SHALL, SHALL NOT, SHOULD, SHOULD NOT, RECOMMENDED, MAY, and OPTIONAL in this document are to be interpreted as described in RFC 2119.
