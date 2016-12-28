# Datadog - Magento 

Datadog Magento integration handles sending events and metrics to Datadog from within the Magento application.

This was adopted from the https://github.com/magento-hackathon/Hackathon_Datadog project.

## List of Metrics
* Page Action: sends $action->getFullActionName()
* Product View: Includes primary SKU
* Product Send to Friend: Includes primary SKU
* Customer Login
* Order Placed: Sends total (Twice?)

## List of Events

## Compatibility
CE 1.9.x   (TBD)


## License

OSL v3, see `LICENSE_OSL.txt`.

## Requirements

* Have an account on Datadog <https://www.datadoghq.com/>. (**with invitation!!**, ask <jacques@monsieurbiz.com>)

## History

* Based on the Datadog project - Magento Hackathon Zürich 2014
https://github.com/magento-hackathon/Hackathon_Datadog

