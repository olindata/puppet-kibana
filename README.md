# Kibana Puppet Module

This module manages [Kibana](http://www.elasticsearch.org/overview/kibana/) a highly frontend scalable for [Logstash](http://logstash.net/) and [ElasticSearch](http://www.elasticsearch.org/).

This module was heavily reworked for Kibana 3 which made of client side javascript only.

## Basic usage

You can install kibana in a directory shared by a web server:

    class {'::kibana':
      install_path => '/var/www/html/kibana/',
    }

## Dependencies

None.

## Contributing

Please report bugs and feature request using [GitHub issue
tracker](https://github.com/camptocamp/puppet-kibana/issues).

For pull requests, it is very much appreciated to check your Puppet manifest
with [puppet-lint](https://github.com/rodjek/puppet-lint) to follow the recommended Puppet style guidelines from the
[Puppet Labs style guide](http://docs.puppetlabs.com/guides/style_guide.html).

## License

Copyright (c) 2012 <mailto:puppet@camptocamp.com> All rights reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
