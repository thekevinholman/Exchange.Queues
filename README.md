# Exchange.Queues 15.0.669.23

## [Download Here][Download]

[Download]: https://github.com/thekevinholman/Exchange.Queues/releases/download/15.0.669.23/Exchange.Queues.mp

### Management Pack to Monitor Exchange Queues on Exchange 2013 and later

This management pack discovers an Exchange Queue Server if there is a Hub Transport or Edge Server role present.
It then monitors and collects performance data for the critical Exchange Transport Queues.

The monitor thresholds are all set to 5000 queue items by default, and will need to be customized for your environment.

* External Aggregate Delivery Queue Length (All External Queues)
* External Retry Remote Delivery Queue Length
* Internal Aggregate Delivery Queue Length (All Internal Queues)
* Internal Retry Remote Delivery Queue Length
* Retry Non-Smtp Delivery Queue Length
* Retry Mailbox Delivery Queue Length
* Submission Queue Length
* Unreachable Queue Length

Version History:

* 15.0.669.22 - Initial release
* 15.0.669.23 - Fixed bug in Queue server discovery
