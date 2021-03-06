---
title: "The Host record for the local computer cannot be found in the DNS database [HostRecordMissing]"
ms.author: dstrome
author: dstrome
manager: serdars
ms.date: 12/20/2016
ms.audience: Developer
ms.topic: reference
f1_keywords:
- 'ms.exch.setupreadiness.HostRecordMissing'
ms.prod: exchange-server-itpro
localization_priority: Normal
ms.assetid: 2f18cb65-29fe-4b72-8d68-52fd503d5673
description: ""
---

# The Host record for the local computer cannot be found in the DNS database [HostRecordMissing]

Microsoft Exchange Server 2016 Setup can't continue because the Host (A) record for this computer can't be found in the Domain Name System (DNS) database.
  
Exchange 2016 Setup requires that the local computer have a valid HOST (A) record registered with the authoritative DNS database for the domain.
  
Exchange depends on DNS Host (A) records for the IP Address of its next internal or external destination server.
  
To resolve this issue:
  
- Verify that the local TCP/IP configuration points to the correct DNS server. For more information, see [Configure TCP/IP settings](https://go.microsoft.com/fwlink/p/?linkid=108281).
    
- Use Nslookup.exe to verify that the Host (A) record exists on the DNS server. For more information, see [To verify A resource records exist in DNS](https://go.microsoft.com/fwlink/?LinkId=63001).
    
For information about DNS name resolution, troubleshooting, and Host (A) records, see the following:
  
- [Troubleshooting DNS](https://go.microsoft.com/fwlink/p/?LinkId=294828)
    
- [Managing resource records](https://go.microsoft.com/fwlink/p/?LinkId=294829)
    
Having problems? Ask for help in the Exchange forums. Visit the forums at: [Exchange Server](https://go.microsoft.com/fwlink/p/?linkId=60612), [Exchange Online](https://go.microsoft.com/fwlink/p/?linkId=267542), or [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?linkId=285351).
  
Did you find what you're looking for? Please take a minute to [send us feedback](mailto:ExchangeHelpFeedback@microsoft.com&subject=Exchange%202016%20help%20feedback&Body=Thanks%20for%20taking%20the%20time%20to%20send%20us%20feedback!%20We%20strive%20to%20respond%20to%20every%20message%20we%20receive,%20even%20though%20it%20might%20take%20us%20a%20while.%20Let%20us%20know%20what%20you%20think%20about%20Exchange%20content:%20What%20are%20we%20doing%20right%3F%20How%20can%20we%20make%20help%20better%3F%0APlease%20note%20that%20we're%20unable%20to%20respond%20to%20requests%20for%20support%20submitted%20via%20this%20email%20address.%20If%20you%20need%20help,%20please%20contact%20Exchange%20Server%20support%20at%20http://go.microsoft.com/fwlink/p/%3FLinkId=402506.%0AThanks!%0AThe%20Exchange%20Server%20Content%20Publishing%20team) about the information you were hoping to find.
  

