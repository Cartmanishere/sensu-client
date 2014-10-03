# sensu-client

A library to send alerts to sensu-client.

## Installing

    [helpshift/sensu-client "0.9.0"]

## Usage

    '(require [sensu-client.core :as sensu])

    (sensu/send-alert :critical "host2 is down"
                      :host "sensu.company.com"
                      :port 3030
                      :name "host2-uptime-check"
                      :refresh 60
                      :occurrences 1
                      :proto :udp)

## License

Copyright © 2014 Helpshift Inc.

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
