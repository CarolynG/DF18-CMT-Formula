# DF18-CMT-Formula
Demo code for the Dreamforce '18 "Become a super-star Admin with Custom Metadata Types" session. Session link: https://success.salesforce.com/sessions?eventId=a1Q3A00001XoCSUUA3#/session/a2q3A000001WXVXQA4

This repo contains two SFDX projects, which represent the state of metadata in the org before and after this demo. These projects are in SFDX "source" format, ready to be deployed to a scratch org.

"beforeProject" contains a custom formula field on the Order object, which contains hardcoded values to determine the shipping cost for the order. It also contains a custom metadata type called "Shipping Policy," which we'll use in the demo to replace the hardcoded values in the formula.

In "afterProject," we've created custom metadata records in the "Shipping Policy" type, and we've replaced the hardcoded values in the Order formula with references to those custom metadata records.
