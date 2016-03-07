---
layout: post
title: BC ICM Footnote
date: '2013-04-19T10:13:00.000-07:00'
author: Paul Ramsey
tags:
- integrated case management
- deloitte
- bc
- mcfd
- enterprise IT
- icm
modified_time: '2013-04-19T10:44:08.876-07:00'
blogger_id: tag:blogger.com,1999:blog-14903426.post-3090153564151268641
blogger_orig_url: http://blog.cleverelephant.ca/2013/04/bc-icm-footnote.html
---

Early this year, the [ICM project](http://www.integratedcasemanagement.gov.bc.ca/) released a [system assessment report](http://www.integratedcasemanagement.gov.bc.ca/documents/icm-mcfd-iar.pdf)&nbsp;from Queensland Consulting which was [seized on by the BCGEU](http://www.bcgeu.ca/ICM_interim_report_120124) and others as showing ICM to be "deeply flawed and serious question remain regarding the software’s suitability for child protection work".

I found two things curious about the Queensland report: first, it was willing to talk about the [failing of COTS](http://blog.cleverelephant.ca/2013/01/cots-uber-alles.html) methodology in a way that is rare in the stodgy conservative world of enterprise IT; and second, a large number of the process recommendations were reiterations of a previous report, a "Readiness Assessment" by Jo Surich, Victoria tech *eminence grise *and former BC CIO. &nbsp;If the Surich report was so good that Queensland was quoting from it rather than writing their own material, I wanted to read it, so I filed an FOI.

You can [read the full Surich report now](http://docs.openinfo.gov.bc.ca/D19070713A_Response_Package_CFD-2013-00140.PDF), on the BC open info site.

I found two items&nbsp;of particular interest&nbsp;in Surich's report.

First, the date. Surich reported out in April of 2011. Over a year later, the Queensland consultants were re-iterating many of his recommendations. **Surich was not listened to.**&nbsp;Since a second set of consultants saw the same problems Surich did, letting his recommendations gather dust was a tactical error, to say the least.

Second, the big picture plan. Surich notes that, in addition to replacing all the tracking and reporting systems used in child protect, the Ministry was simultaneously changing the practice model (the "business process", in the usual IT terminology) that social workers use for their cases.

Simultaneously changing the business process and technology is a time honoured and widely replicated **failure mode** in enterprise IT development, because it makes so much sense. &nbsp;If you're changing the business process, you'll need to change the systems to match the business process. &nbsp;So, why not **replace**&nbsp;the systems at the same time as you change the business process?

Lots of reasons!

<ul><li>Your mutating business process will constantly change the system requirements underneath you, resulting in lots of back-tracking and re-coding.&nbsp;</li><li>You won't know if your business process is bad until you deliver your system, which will then require further system changes as you again alter the business process.</li><li>You double down on changes your staff need to ingest, in both tooling and methodology, and triple down as you add in fixes to business process after deployment.</li><li>It's been done before, and it's led to some [epic, epic failures](http://spectrum.ieee.org/computing/software/who-killed-the-virtual-case-file/0).</li></ul><div><br />As I learn more about the background to ICM, I have to ask myself if I would have done any differently. Particularly given the timelines and promises that backstop the huge [capital commitment](http://blog.cleverelephant.ca/2012/12/is-building-enterprise-systems-capital.html) that gave birth to ICM, I find myself saying "no", I'd have made the same (similar) mistakes. I'd have walked down a very similar path. Probably not using COTS, but still trying to do business process and technology at once, trying to deliver a complete replacement system instead of evolving existing ones. Taking a set of rational, correct, defensible decisions leading down a dead-end path to failure.</div><div><br /></div>