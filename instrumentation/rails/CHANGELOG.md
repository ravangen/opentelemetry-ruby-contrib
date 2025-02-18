# Release History: opentelemetry-instrumentation-rails

### v0.24.1 / 2023-01-14

* DOCS: Fix gem homepage 

### v0.24.0 / 2022-12-06

* BREAKING CHANGE: Remove enable_recognize_route and span_naming options 

* FIXED: Remove enable_recognize_route and span_naming options 

### v0.23.1 / 2022-11-08

* FIXED: Bump rails instrumentation dependency on action_pack instrumentation 

### v0.23.0 / 2022-10-14

* ADDED: Name ActionPack spans with the HTTP method and route

### v0.22.0 / 2022-06-09

* Upgrading Base dependency version
* FIXED: Broken test file requirements 

### v0.21.0 / 2022-05-02

* ADDED: OTel Railtie 
* FIXED: RubyGems Fallback 

### v0.20.0 / 2021-12-01

* ADDED: Move activesupport notification subsciber out of action_view gem 
* FIXED: Instrumentation of Rails 7 

### v0.19.4 / 2021-10-06

* (No significant changes)

### v0.19.3 / 2021-09-29

* (No significant changes)

### v0.19.2 / 2021-09-29

* (No significant changes)

### v0.19.1 / 2021-09-09

* (No significant changes)

### v0.19.0 / 2021-08-12

* ADDED: Instrument active record
* ADDED: Add ActionView instrumentation via ActiveSupport::Notifications
* FIXED: Rails instrumentation to not explicitly install sub gems
* DOCS: Update docs to rely more on environment variable configuration

* This release adds support for Active Record and Action View.
* The `enable_recognize_route` configuration option has been moved to the ActionPack gem.
* See readme for details on how to configure the sub instrumentation gems.

### v0.18.1 / 2021-06-23

* FIXED: Updated rack middleware position to zero 

### v0.18.0 / 2021-05-21

* ADDED: Updated API depedency for 1.0.0.rc1

### v0.17.0 / 2021-04-22

* ADDED: Added http.route in rails instrumentation to match the spec
* FIXED: Rails example by not using `rails` from git
* FIXED: Updated rack middleware position to zero

### v0.16.0 / 2021-03-17

* FIXED: Example scripts now reference local common lib
* DOCS: Replace Gitter with GitHub Discussions

### v0.15.0 / 2021-02-18

* (No significant changes)

### v0.14.0 / 2021-02-03

* (No significant changes)

### v0.13.0 / 2021-01-29

* (No significant changes)

### v0.12.0 / 2020-12-24

* (No significant changes)

### v0.11.0 / 2020-12-11

* FIXED: Rails tests
* FIXED: Copyright comments to not reference year

### v0.10.0 / 2020-12-03

* FIXED: Otel-instrumentation-all not installing all

### v0.9.0 / 2020-11-27

* Initial release.
