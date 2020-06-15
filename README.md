# Content

The Freedom-of-Information scraper toolkit (aka *foiscraper*) is a web scraper that is able to fetch data from any website you can access in your webbrowser.

It is able to parse dynamic frontend data with simple XPath/Schema.org based data transfer definitions. The parser is protected by the Tor Onion network to hide it's identity and allow undisturbed parser operation.

The data is provided in an Elasticsearch/Kibana based storage.

# Manifest

When Tim Berners-Lee created the world wide web it was envisioned as an open platform storing semantic data for easy exchange with other (scientific) communities.

The development of increasingly dynamic and style-driven web platforms destroyed the open data potential due to the increased coupling between data and render layers.

Nowadays schemantic data definition frameworks like Schema.org provide means to let platform providers open up their lakes.

Unfortunately this is only utilized as opportunistic if-it-sees-fit push mechanism of selective data sets, usually as required by search engines to properly index the platform.

The same platform providers monetizing the largest personal information datasets are often the most restrictive in giving away their own data in processable manner. 

It is Norman Luhrmann's intention to bring back the freedom of the Gopher/Netscape era by providing a rock-solid data scraper toolkit that you can, with confidence, simply point to the public facing parts of a large website and have it fetch the data you are interested in.

# Collaboration

NORMAN.RESEARCH will provide a MVP PoC implementation that is tested against a multitude of more or less strictly protected platforms.

Milestone goals:

1. Resilience against scraper protection
2. Ease of data transfer definition
3. Ease of data reporting/exporting
4. Ease of resync of existing dataset

After this milestone we hope to find supporting developers for the future growth and maintenance of this repository.

```
#digitalstrike
```
