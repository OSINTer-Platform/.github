# OSINTer
[![OSINTer](https://raw.githubusercontent.com/OSINTer-Platform/OSINTer/master/logo/full.png)](https://osinter.dk)

## Contributing
As OSINTer is open-source we highly encourage
any form of contributing. Should you want to contribute, then please get involved with this GitHub or get in
contact either at contact@osinter.dk or on the Github repos (if you are reading
this on Gitlab, then that is simply a downstream mirror).

## Introduction
OSINTer is an open-source intelligence
gathering tool, designed to ease the intelligence gathering process by scraping
reliable intelligence news sources, and presenting them in an easy to navigate
UI, hosted as a web-application, to allow intelligence analysts to handle large
amounts of intelligence.

OSINTer is split into multiple repositories for ease of development, listed
below:
| Repository | Description |
| --- | --- |
| [OSINTansible](https://github.com/OSINTer-platform/ansible) | Responsible for making the installation process easier, by using ansible. |
| [OSINTbackend](https://github.com/OSINTer-platform/backend) | Responsible for the scraping and initialization of OSINTer. |
| [OSINTmodules](https://github.com/OSINTer-platform/modules) | Responsible for cross-repo functionality. |
| [OSINTapi](https://github.com/OSINTer-platform/api) | Responsible for displaying the intelligence in an easy to view format.|
| [OSINTwebfrontend](https://github.com/OSINTer-platform/webfrontend2) | Responsible for displaying the intelligence in an easy to view format.|
| [OSINTprofiles](https://github.com/OSINTer-platform/profiles) | Responsible for specifying the various sources that are scraped for intelligence. |
| [OSINTblog](https://github.com/OSINTer-platform/blog) | Responsible for the content at the blog associated with OSINTer |


 For a demonstration of how it looks and works, have a look at our demo-site at
 [OSINTer.dk](https://osinter.dk)

## What problem does OSINTer attempt to solve?
The process of gathering cyber threat intelligence is only as successful as the
investigators ability to identify relevant intelligence sources. Identifying
relevant and reliable sources could often be a time-consuming task, as the CTI
personnel would have to first locate the intelligence source, then read it to
identify its relevance and usefulness as well as identify its formatting, and
finally mark down all relevant details for usage in their report. This is time
consuming and can be hit and miss depending on the skill and experience of the
CTI personnel, and while products to combat this repetitive and time-consuming
task, like Recorded Future, exists, these are often not only expensive, but
also closed in nature, as they rarely integrate well with third-party
utilities.

The goal of OSINTer is to build an extensible platform for
collecting and organizing open-source intelligence in a way that easily
integrates with third-party utilities and other pieces of open-source software.

## How does OSINTer Solve the Problem?
OSINTer solves this problem through a system that automatically gathers
information from known, reliable sources and organizes it in an easily
accessible, user-friendly interface, allowing users to quickly and efficiently
identify relevant intelligence. It archives the content from the threat
intelligence sources, which is retrievable for the user for later analysis. The
archived content is available as downloadable Markdown files that users can
import into any Markdown editor for evaluation. It also enables user
customization and integration with third-party utilities.

Additionally, OSINTer uses machine learning pipelines to better
handle and organize the large volume of data collected, making it even more
user-friendly and efficient. 

The platform ultimately aims to take the burden of manual data collection off
the user, freeing up time and resources while delivering a highly efficient,
automated process for collecting valuable intelligence data.
