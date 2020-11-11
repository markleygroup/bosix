# Boston Internet Exchange (BOSIX) IRR Queries

The BOSIX route servers only accept validated routes in the IRR maintained by [Merit RADb](https://www.radb.net/). Twice daily at 0600 and 1800 EST, we query the list of participant ASNs against this database and publish those results here. We then build prefix lists based on the aggregated results of those queries. As a result, our route servers only accept prefixes present in these queries. If you're unsure as to which prefix lists we're currently importing, you may find the list here. 

For details on the Boston Internet Exchange, see: https://www.markleygroup.com/services/boston-internet-exchange

For more information on our implementation of IRR and RPKI, see: https://www.markleygroup.com/services/boston-internet-exchange/irr-rpki

For assistance, see: https://www.markleygroup.com/contact-markley
