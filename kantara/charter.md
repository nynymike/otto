# Kantara OTTO Charter

## WG NAME

Open Trust Taxonomy for OAuth2 (OTTO)

## PURPOSE

The working group will develop the basic structures needed for the creation of multi-party federations between OAuth2 entities. The intent is to create a foundation of trust and drive down the cost of collaboration by publishing technical and legal information. These structures will include the set of APIs and related data structures enabling an OAuth entity to manage which entities it trusts and for other OAuth entities to discover members of the federation and details of the services.

The Work Group is necessary to bring together collaborators from existing SAML federations and the OAuth community to collaborate on a draft solution that meets their shared goals in this area and takes into account lessons learned from the past ten years of SAML.

Specifically, this Work Group is responsible for:
* Developing a set of use cases and requirements that are specific enough to guide the specification design work
* Developing a set of modular draft specifications meeting these use cases and requirements
* Overseeing the contribution of each resulting draft specification to a standards-setting organization

The group will target completion of the specifications by 1/15/16.

## SCOPE

The APIs and data structures will enable discovery of the members of the federation and details about their services, key material and technical capabilities. The final scope will be refined after consideration of the use cases. 

Existing SAML Federation XML structures will inform this work, but the data structures will not be expressed in XML but in JSON. The functions supported in existing SAML federations should be supported. Additionally, support for a more efficient and scalable discovery process and dynamic integration process will be considered.

## DRAFT TECHNICAL SPECIFICATIONS

The following technical specifications should be produced, with modular spec boundaries subject to change.  The specifications will then be submitted to appropriate standards bodies for further work and completion:
 
- Open Trust Taxonomy for OAuth2 Use Cases
- Open Trust Taxonomy for OAuth2 Core Specification

## LEADERSHIP

- Co-Chair, Michael Schwartz
- Co-Chair, Janusz Ulanowski, HEAnet

## AUDIENCE

Existing federation operators and any group of autonomous organizations that need to establish common policies and procedures to establish a basis for trust and faciliate electronic collaboration.

## DURATION 

Working Group would dissolve shortly after the finalization of the standard.

## IPR POLICY 

Option Patent and Copyright Reciprocal Royalty Free with Opt-Out to (RAND)

## RELATED WORK AND LIAISONS 

There is an existing multi-party federation standard for SAML. The WG will also leverage the UMA 1.0 and OpenID Connect 1.0 standards, although no specific liaison is needed. There may be some synergies with the OASIS Trust Elevation TC regarding implementation guidelines for authentication to enable trust elevation across federation members. 

## CONTRIBUTIONS: 

none

## PROPOSERS

- Michael Schwartz
- Keith Hazelton, Internet2
- Janusz Ulanowski, HEAnet
