# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.7](https://github.com/jearle10/shopify/compare/shopify-v0.1.6...shopify-v0.1.7) - 2023-07-29

### Added
- add ShipmentStatus::LabelPrinted
- make GetPage: Clone
- new pagination support; upgrade Product & Variant api to 2020-07
- request_raw

### Fixed
- fix order Property::value type

### Other
- Update Cargo.toml
- Update Cargo.toml
- Ignore failing test - dependent on dummy shopify instance setup
- Resolve compile error within order module
- update fulfilment module test with new fields (sku sharing and order opt in)
- Resolve compiler errors with tests in inventory module
- add new fields
- Support new FulfillmentOrder API
- sku is nullable
- more nullable
- country is nullable
- Shopify schema changes
- body_html is nullable
- Order risk api
- Property value is nullable.
- rust 2018, reqwest 0.11, thiserror
- first name is optional
- shipping line source is optional
- optional fields
- add OrderApi::get
- fix an error caught in production
- create_fulfillment, update_fulfillment accept &NewFulfillment
- Make NewFulfillment Clone
- :tracking_urls
- :location_id
- Make enum Copy, Clone, PartialEq
- Should retry on Io error.
- Fix a typo.
- Inventory API initial
- Address.country_code is nullable.
- Fix test TMP_DIR
- 0.2.0
