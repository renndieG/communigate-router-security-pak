#DKIM SETUP

# Introduction #

Helper Apps for DKIM setup info


# Details #

**Configuring CommuniGate Pro:
> Create a helper:
> > Name: DKIM\_verify
> > Program Path: /usr/bin/perl helper\_DKIM\_verify.pl**

[CommuniGate Pro Helper setup info](http://www.communigate.com/cgatepro/Helpers.html)



> Then create a server-wide rule:
> > [Data: [Header field](.md) [is](is.md) [DKIM-Signature:**]
> > > Action: [ExternalFilter](ExternalFilter.md) DKIM\_verify]**

[CommuniGate Pro Rules setup info](http://www.communigate.com/cgatepro/Rules.html)