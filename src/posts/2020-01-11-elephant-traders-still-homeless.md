---
layout: posts
title: Elephant traders still homeless
date: 2020-01-20
description: "Survey shows two-thirds of current traders have nowhere to go."
image: img/latinelephantmap.png
---
As Delancey [announces](https://www.london-se1.co.uk/news/view/10081) its intention to close down the E&C shopping centre, research by [Latin Elephant](https://latinelephant.org/)/[petit elephant](https://twitter.com/elephant_petit/status/1118825370017386496) has shown that only around 40 out of nearly 100 independent traders still operating at the centre have been allocated new premises.

Latin Elephant's web-page has an [interactive map](https://latinelephant.org/map/#Q5), accompanied by supporting evidence, which narrates the decline in trader's numbers, up to late spring 2019.  Latin Elephant’s figures show that there were originally 130 independent traders operating in January 2018, of whom only around 40 will be relocated, if the relocation strategy continues on its present course.  

![](https://35percent.org/img/latinelephantmap.png)

## How many traders?

The figure of 130 independent traders (ie traders with less than three outlets) was [supplied by Southwark Council](https://pbs.twimg.com/media/DwEQ6HqW0AEbC6W.jpg:large) in January 2018 and later confirmed by officers at planning committee in July.  These include market stallholders and businesses in Hannibal House, the office block above the centre, and all lie within the so-called 'red-line' of the proposed redevelopment area.  Latin Elephant, with the assistance of petit elephant, then conducted its own survey in December 2018, just before the redevelopment was finally granted planning permission. This found [only 97 traders remained]( https://latinelephant.org/map/#Q1) indicating a loss of 30 traders over a few months.

In March 2019, Southwark responded to [a Freedom of Information](https://www.whatdotheyknow.com/request/independently_owned_retail_busin?nocache=incoming-1334948#incoming-1334948) (FOI) request, with a [database](https://www.whatdotheyknow.com/request/555280/response/1334948/attach/2/190321%20For%20FOI%20EC%20traders.pdf%201037530.pdf) of 79 'independent local operators', eligible for relocation funds as defined by the legal agreement between Southwark Council and developer Delancey; Latin Elephant identified a further [21 independent businesses omitted](https://latinelephant.org/map/#Q7) from this list.  

Latin Elephant/[petit elephant](https://twitter.com/elephant_petit/status/1184572253381500928) also consider that 17 more businesses are excluded from relocation funding, simply by the wording of the legal agreement. These includes sub-tenants in Arch 7, on Elephant Road, and small traders in the shopping centre that rent their space through third parties, such as Forum CentreSpace Ltd.

In any event, in March 2019, Southwark confirmed that [only 36](https://twitter.com/kieronjwilliams/status/1108781273630289920?s=12) of the 79 'independent local operators' had been offered a relocation unit.

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<link href="https://cdn.datatables.net/1.10.19/css/jquery.dataTables.min.css" rel="stylesheet">

<div id='visualization' style="width: 100%, height: 100%"></div>

<script>

google.charts.load('current', {packages: ['corechart']});
google.charts.setOnLoadCallback(drawAnnotations);

function drawAnnotations() {
// Create and populate the data table.
var data = new google.visualization.DataTable();

data.addColumn('date', 'Date');
data.addColumn('number', 'Independent businesses');
data.addColumn({type: 'string', role: 'annotation'});
data.addColumn({type: 'string', role:'tooltip', 'p': {'html': true}});
data.addRow([new Date(2018, 0, 18), 130, '130', createCustomMessage(130, 'Date: January 2018<br>Source: Southwark Council email to Latin Elephant')])
data.addRow([new Date(2018, 11, 12), 79, '79', createCustomMessage(79, 'Date: 12 Dec 2018 (Planning Subcommittee B)<br>Source: Freedom of Information Request')])
data.addRow([new Date(2019, 2, 21), 36, '36', createCustomMessage(36, 'Date: 21 March 2019<br>Traders with relocation space as of April 2019')])

// // Create and draw the visualization.
  
  var options = {title: 'Southwark Council figures of independent businesses over time',
  //width: 100%, 
  height: 400,
  //colors: ['#fb9a99'],
  chartArea: {left:50, width: "60%", height: "70%" },
  vAxis: {title: "Businesses"},
  //hAxis: {title: "Time"},
  lineWidth: 1,
  tooltip: { isHtml: true },
  legend:'none'
  };
var chart = new google.visualization.ScatterChart(document.getElementById('visualization'));
chart.draw(data, options);

function resizeHandler() {
chart.draw(data, options); 
};

if (window.addEventListener){
window.addEventListener('resize', resizeHandler, false);
}
else if (window.attachEvent){
window.attachEvent('onresize', resizeHandler);
}
}

function createCustomMessage(totalTraders, message){
return '<div style="padding:5px 5px 5px 5px; font-family: Arial; font-size:12px">Businesses: <b>' + totalTraders+ '</b><br>' + message + '</div>';
}
</script>

## Not enough relocation space

Even though Latin Elephant has voiced concerns about the shortage of relocation units on many occasions, both before and after planning approval, only 40 units are being provided on three sites.  Latin Elephant identify 12 units in  Perronet House, 8 in Elephant One, and 20 in Castle Square. 

In addition to these sites Southwark claim that Lendlease's [Elephant Park](https://www.elephantpark.co.uk/about-elephant-park/) development (formerly the Heygate estate) offers 1,350 sq m of affordable retail space, but this only equates to eight units, at most.  To date, none of the Elephant Park units has been offered to traders affected by the shopping centre redevelopment, according to an [FOI response](https://docdro.id/R6YTe4e) to a [Southwark Law Centre](https://www.southwarklawcentre.org.uk/) question.  Thirty market pitches in East St market were also suggested by Delancey in its planning application, but these are nearly a mile away and have never been delivered. 

## Unfit database

Delancey has also a legal obligation to maintain a database of vacant retail properties and make it available to eligible traders. Even though Southwark Council says on its [regeneration webpage](https://www.southwark.gov.uk/regeneration/elephant-and-castle?chapter=20) that properties are in the borough and within one mile of the shopping centre, petit elephant found that as of June 2019 many did not meet these criteria. Moreover, many demanded rents between £50,000 and £100,000 per annum, which Latin Elephant has already submitted are beyond the means of small-sized businesses.  The whole list of 54 relocation units in the database is [here](https://twitter.com/elephant_petit/status/1135529323220176896).

So, the best-case scenario is that less than half of all independent traders within the red line have been relocated to premises that might be more or less suitable for their businesses, with all other traders looking at options some distance away and/or too expensive.

## Not enough money

Another obstacle to successful relocation is the cost of moving, fitting-out new premises and re-establishing the business.  The relocation fund provided by Delancey stands at [£634,700](https://www.southwark.gov.uk/regeneration/elephant-and-castle?chapter=20), with a vague commitment to an unspecified greater amount, after _‘all claims have been properly assessed’_ and _‘taking into account genuine trader hardship’_.  This averages out at a £17,630 per trader, given thirty-six traders and a very modest £8,034, given 79 traders.  In fact, the costs will of course vary, according to size and other needs. By way of example, one business was quoted £121,000 including VAT, for the fit-out works of a 65 sq m unit at Elephant Park.

![](https://35percent.org/img/traderscomp.jpeg)

## Feeble enforcement from Southwark Council

The trader' relocation strategy was inadequate from the start, with too little space to move to and too little money to do it with, but it has been made worse by ineffectual enforcement by  Southwark Council.

The relocation process is effectively controlled by Delancey and, in the case of Elephant Park premises, fellow developer Lendlease. Both [developers have obligations](https://www.southwark.gov.uk/regeneration/elephant-and-castle?chapter=20) to provide affordable retail premises to shopping centre traders, under their respective legal s106 development agreements with Southwark Council.  Southwark therefore has the power to take action if it thinks that these obligations are not being fulfilled.  Traders complain that this is indeed the case, with shopping centre traders not fitting the retail profile required by Delancey and Lendlease for the new Elephant developments.  [Southwark Law Centre](https://www.southwarklawcentre.org.uk/) has taken up the case of one trader, refused premises because of the nature of their trade.

Even those traders who have been allocated space have justifiable complaints about its size, cost and position - all critical factors for successfully continuing business. In particular, there are complaints about Perronet House.  Despite being owned by Southwark Council, who is thus the traders' new landlord, both the [service charges and rent](https://docdro.id/5AQJ8yg) will be higher there than those for Castle Square, the relocation site owned by Delancey. For example, the rent of a 26 sq m unit on the ground floor in Castle Square is £6,768 per annum, plus £2,256 of service charge (£8 per square foot), while Southwark Council offers a 25.7 sq m unit in Perronet House at an average of £7,645 over 5 years, with an ‘estimated’ service charge of £3,047 (£11 per sq ft).

## What information does Southwark Council hold?

Several FOI requests have been made to Southwark, in pursuit of information about the traders' relocation. The [latest request](https://www.whatdotheyknow.com/request/independent_traders_in_elephant?unfold=1#incoming-1456513) is for information about which traders have succeeded in their [relocation requests](https://www.scribd.com/document/443429607/Summary-of-the-allocation-process) (thirty-six in number), those refused (28 in number), those who have left the Elephant and Castle, plus the 130 Elephant traders initially identified by Southwark, back in January 2018.  Perhaps unsurprisingly this request has been refused, on the grounds that it would prejudice the commercial interests of unspecified third parties; an appeal has been made against the decision.

## A bad tale continues

An [Evening Standard article](https://www.homesandproperty.co.uk/area-guides/southwark-borough/elephant-and-castle/living-in-elephant-castle-area-guide-to-homes-schools-and-transport-links-a135826.html), enthusiastically [endorsed by Southwark Council leader Peter John](https://twitter.com/peterjohn6/status/1214971921277890560), tells the shopping centre redevelopment story that developer Delancey wants the world  to believe in - new homes, new jobs, 'funky street food'.  Through their diligent research Latin Elephant and petit elephant tell a different story; one of [neglect and broken promises](https://35percent.org/2017-04-02-traders-charter-broken-promises/). The independent  traders, their families, customers and the social fabric they have built over many years is being pulled apart to enable Delancey and Southwark's idea of a bright future. 

But it is not too late for Southwark to partly redeem themselves - the traders need more space and more money for their relocation fund.  Delancey (and Lendlease) are well able to provide it.  Delancey's anticipated profit from the shopping centre redevelopment is at [least £137.1m](https://35percent.org/2018-07-02-viability-and-delancey/).

The [Up the Elephant campaign](https://twitter.com/UpTheElephant_) will be holding a stall on **Saturday, 25 January 11.30pm** just outside the **former Charlie Chaplin pub**, on the **New Kent Rd side of the shoppin centre**.

There will also be a [demonstration, organised by the Up The Elephant campaign](https://twitter.com/UpTheElephant_), in support of the traders' deputation to Southwark Council's first assembly meeting of the year on **Tuesday 28 January Southwark Council Head Offices, Tooley St 6pm** - everyone who wants a fairer, inclusive regeneration at the Elephant is welcome.

![](https://35percent.org/img/jan2020protest.jpg)
