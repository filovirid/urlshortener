# URLSHORTENER
A curated list of URL Shortener Websites with responses for crawling

## Use Case

If you are writing a crawler or any kind of system that detecting a URL shortener is important,
then this list can help you!

## Description of the files

1. names.txt

This file contains only the registered domain name for the URL shortener. The list **ONLY** contains the destination
URL not the website itself. For example, _bitly.com_ is the name of the Bitly website while the shortened URLs are 
in a form of bit.ly/blahblah. So we have only bit.ly domain in our list not bitly.com

I try to constantly update the list. If a domain name in the list has no "A" record or the website is down,
I will remove it from the list. However, if it's marked as malicious by Google safe browsing service, we still
keep it in the list.

## Contributions

No pull requests. Just open an issue to add a new domain or remove a dead/parked one.


