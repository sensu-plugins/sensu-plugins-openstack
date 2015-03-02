## Sensu-Plugins-openstack

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-openstack.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-openstack)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-openstack.svg)](http://badge.fury.io/rb/sensu-plugins-openstack)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-openstack.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-openstack)

## Functionality

## Files

* bin/check_ceilometer-agent-central.sh
* bin/check_ceilometer-agent-compute.sh
* bin/check_ceilometer-api.sh
* bin/check_ceilometer-collector.sh
* bin/check_keystone-api.sh
* bin/keystone-token-metrics.rb
* bin/check_neutron-api.py
* bin/neutron-agent-status.py
* bin/nova-hypervisor-metrics.py
* bin/nova-server-state-metrics.py

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-openstack -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-openstack`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-openstack' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-openstack' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

## Notes

[1]:[https://travis-ci.org/sensu-plugins/sensu-plugins-openstack]
[2]:[http://badge.fury.io/rb/sensu-plugins-openstack]
[3]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack]
[4]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack]
[5]:[https://gemnasium.com/sensu-plugins/sensu-plugins-openstack]
