# continuent-monitors-munin

## Installation

1. Clone this repository onto each system
2. Symlink the tungsten_latency script into /etc/munin/plugins
3. Create a /etc/munin/plugin-conf.d/tungsten_latency file

    ```
    [tungsten_latency]
    user tungsten
    env.CONTINUENT_ROOT /opt/continuent
    ```