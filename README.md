[![Build Status](https://travis-ci.org/puppetlabs/clj-pcp-common.png?branch=master)](https://travis-ci.org/puppetlabs/clj-pcp-common)

## clj-pcp-common

PCP message codec and protocol helpers

    https://github.com/puppetlabs/pcp-specifications

It supports PCP v1 and v2 via the `message-v1` and `message-v2` namespaces. The `protocol` namespace defines a common
definition for both versions of the protocol; note that some message types have been removed from v2.

## Installation

To use this service in your trapperkeeper application, simply add this
project as a dependency in your leiningen project file:

[![Clojars Project](http://clojars.org/puppetlabs/pcp-common/latest-version.svg)](http://clojars.org/puppetlabs/pcp-common)

## Maintenance

Maintainers: Alessandro Parisi <alessandro@puppet.com>, Michael Smith
<michael.smith@puppet.com>, Michal Ruzicka <michal.ruzicka@puppet.com>.

Contributing: Please refer to [this][contributing] document.

Tickets: File bug tickets at https://tickets.puppet.com/browse/PCP and add the
`clj-pcp-common` component to the ticket.

[contributing]: CONTRIBUTING.md
