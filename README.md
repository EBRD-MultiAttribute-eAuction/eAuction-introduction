# Multi-attributes model for electronic auction

In contrast to the single-attribute auction, where each side of the auction knows the preferences of the other side regarding the price (the seller prefers a higher price and the buyer - a lower one), in multi-attribute auctions, the bidders do not necessarily have any information about the buyer’s preferences regarding these additional attributes. To overcome this problem buyers can use an alternative approach - multi-attribute auction. 
As mentioned above, multi-attribute auctions involve introducing additional criteria in the comparison of bids. Such auctions tend to involve virtual costs that typically represent a preference but not a requirement for certain aspects of the bid. In this sense, multi-attribute auctions are like introducing soft qualification requirements, as bidders that meet certain desirable qualities receive a preference for the purpose of bid comparison. It is possible, for instance, to attribute a grade to the bidders’ reputation and past experience rather than imposing a strict requirement, or to offer a bonus to bidders  that use locally manufactured equipment, rather than necessarily introducing hard domestic content constraints. Adding  a set of attributes into the auction, one may think that the multi-attribute auction can be mapped into a simple price only auction. However, this is not the case. The attributes announced by the buyer are not necessarily its real utility function (i.e. the one that reflects the buyer’s actual preferences). These announced attributes are chosen by the buyer in order to minimize its expected pay-off. Thus, the scoring function under announced attributes may have a different structure from the buyer’s utility function or a similar structure but with different weights associated with the various attributes. Moreover, even when given the scoring function, it is still important  for the bidders to identify their  optimal bid.

This concept proposes ways to handle auctions using automated scenarios. In particular - by analyzing three auction protocols, prescribed by EU Directive, for the case of multi-attribute items. 

Another possible protocol is to have a two- or even three-stage protocol, where in the first stage the bidders offer bids using a sealed protocol, then a set of the pre-selected (manually or automatically) bidders get a second opportunity to compete in sequence of “open-cry” auctions.

There might be several such protocols which differ in the reserve price/initial bid allowed in the second stage. 

## Types of attributes in multi-attribute auction

In multi-attribute auctions, the subject is defined due to a set of attributes as an item characterized by several negotiable dimensions, in addition to the price, that is determined in the auction process. For example, in the supply chain management domain, contracts are typically composed of multiple negotiable attributes: supply time, number of items delivered, duration of the product’s warranty and the price. Generally, the attributes involved during the auction can be classified between: verifiable, unverifiable or authority-provided attributes.

### Attribute typologies in multi-attribute auctions

For all of the attributes, as they all influence the winner determination problem of multi-attribute auctions, two main criteria can be distinguished: attribute ownership, and verifiability. Ownership means that attributes can be characterized according to the information source (the Authority itself or the tenderers). On the other hand verifiability concerns the capability of an attribute to be verified. Regarding ownership, attributes can be classified as authority-provided or tenderer-provided:

**Authority-provided attributes**

This is the set of attributes which Authority uses to achieve two objectives: to qualify submitted by tenderer data, e.g. self-declaration according to European Single Procurement Document (ESPD) and to calculate a base value of the received bids  according to a given objective criteria. 

**Tenderer-provided attributes**

They are the set of attributes that bidders express regarding the qualification of the subject according to a predefined set of criteria and its ranges of weightings. Such attributes can be, in turn, classified according to the capability of the auctioneer to verify them.

- Unverifiable tenderer attributes. These are the set of attributes defined by tenderer whose true values are only known by the tenderer itself. A typical example of this kind of attribute is the economic value which a tenderer offers to obtain an item or for providing a service - the price offer itself. 
- Verifiable tenderer attributes. These are the set of attributes which are defined by tenderer whose true value can be known and checked by Authority. Examples of this type of attribute are delivery times, electricity consumption or other physical specifications. As these attributes can be checked, they can be used to adjust evaluation of tenderers and their offers.

