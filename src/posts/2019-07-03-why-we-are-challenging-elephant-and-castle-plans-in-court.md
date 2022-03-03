---
layout: posts
title: "Why we're challenging the Elephant & Castle redevelopment plans in court"
date: 2019-07-03
image: img/lovetheelephantbanner.jpg
excerpt: Southwark Council - demolishing council homes, generating better people 
---

Twenty years ago, Fred Manson, Southwark Council's Director of Regeneration laid out the aims of the Labour council's new regeneration strategy in industry magazine, the Estates Gazette: _"We need to have a wider range of people living in the borough"_ because _"social housing generates people on low incomes coming in and that generates poor school performances, middle-class people stay away."_ As the Gazette reported it, this was _"part of a deliberate process of gentrification that will result in social housing being replaced by owner occupied dwellings and developers being given free rein to build luxury flats"_ [^1].

Since Mr Manson's 1999 anti-council housing manifesto, the borough has lost more than 13,000 council homes (see graph below) and the proportion of council housing had fallen from 60% of to [28% of housing stock](https://www.southwark.gov.uk/assets/attach/2683/Southwark_Housing_Key_Stats_October_v2_2015.pdf) by 2015.  This is mainly the consequence of [Right to Buy](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/759390/LT_685.xlsx) and [void sales](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/561232/LT_648.xlsx). 

But council estate regeneration, Manson style, is also playing its part. The Gazette article mentions three estates south of Tower Bridge earmarked for demolition. At [least eight others](https://35percent.org/the-southwark-clearances) can be added, totalling 7,639 council homes and leasehold properties lost.  The developments replacing these will provide over 11,000 new homes, but only 3,200 of them will be social rented and while Southwark does now have an council house building programme, it is [still knocking down and selling off council homes faster than it is building them](https://35percent.org/2018-11-12-11000-council-homes-manifesto-pledge/).  

The proportion of social rented housing is even lower when other major schemes are considered.  Analysis of the major schemes approved by Southwark over the last 15 years gives [an average social rent component of under 4%](https://35percent.org/major-schemes) out of about twelve thousand homes - well below the Council's [policy requirement of 25%](LINKTONSP).  ([Recent approvals](https://35percent.org/img/OKRapprovals.pdf) of [Old Kent Rd developments](https://35percent.org/2019-06-16-verney-rd-yet-another-old-kent-road-development/) increase the overall percentage to 10%).

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js">
</script>
<script src="https://code.highcharts.com/highcharts.js">
</script>
<script src="https://code.highcharts.com/modules/exporting.js">
</script>

<div id="container1" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>

<script type="text/javascript">

        $('#container1').highcharts({
            title: {
                text: "Southwark's Council Homes",
                x: -20 //center
            },
            subtitle: {
                text: 'Source: <a href="https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx">https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx</a>',
                x: -20
            },
            xAxis: {
                categories: ['1999', '2000', '2001', '2002', '2003', '2004', '2005', '2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015', '2016', '2017', '2018']
            },
            yAxis: {
                title: {
                    text: 'Council-owned stock'
                },
                plotLines: [{
                    value: 0,
                    width: 1,
                    color: '#808080'
                }]
            },
            tooltip: {
                valueSuffix: ' Council homes'
            },
            legend: {
                layout: 'vertical',
                align: 'right',
                verticalAlign: 'middle',
                borderWidth: 0
            },
            series: [{
                name: 'Southwark',
                data: [51706, 50903, 49875, 48052, 46887, 45346, 43885, 42275, 41873, 41287, 40618, 40120, 39845, 39781, 38578, 39029, 38687, 38522, 38553, 38489]
            }]
        });

</script>

## Nearly a thousand new homes, 116 social rented - (maybe)

The [Elephant and Castle shopping centre redevelopment](https://35percent.org/shopping-centre) is no exception in this regard.  A stone's throw from the demolished Heygate estate, only 116 of nearly a thousand new homes will be offered as social rent (8.6% by floorspace), all to be built nearly ten years hence.  Shopping centre owner and _'specialist real estate investment and advisory company developer'_ [Delancey](https://www.delancey.com/welcome.html) said that this was [as much as it could afford](https://planbuild.southwark.gov.uk/documents/?GetDocument=%7b%7b%7b!b5xBNaYRSleWlYx6oXVrEA%3d%3d!%7d%7d%7d) to build, but we now know that with Mayor’s funding they could give us another 42 homes - still a modest amount, but almost enough to reach Southwark's local plan requirement. 

<div id="container2" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<script type="text/javascript">
var colors = Highcharts.getOptions().colors,
  categories = [
    'Private: 65%',
    'Social Rent: 17.5%',
    'Intermediate: 17.5%'
  ],
  data = [
    {
      y: 65.0,
      color: colors[2],
      drilldown: {
        name: 'Market Rent',
        categories: [
         'Market Rent'
        ],
        data: [
          65.0
        ]
      }
    },
    {
      y: 17.5,
      color: colors[1],
      drilldown: {
        name: 'Social Rent',
        categories: [
          'Social Rent',
          'Intermediate Rent'
        ],
        data: [
          8.6,
          0.0
        ]
      }
    },
    {
      y: 17.5,
      color: colors[0],
      drilldown: {
        name: 'Intermediate Housing',
        categories: [
              'Intermediate Rent'
        ],
        data: [
          26.4
        ]
      }
    }
  ],
  browserData = [],
  versionsData = [],
  i,
  j,
  dataLen = data.length,
  drillDataLen,
  brightness;


// Build the data arrays
for (i = 0; i < dataLen; i += 1) {

  // add browser data
  browserData.push({
    name: categories[i],
    y: data[i].y,
    color: data[i].color
  });

  // add version data
  drillDataLen = data[i].drilldown.data.length;
  for (j = 0; j < drillDataLen; j += 1) {
    brightness = 0.2 - (j / drillDataLen) / 5;
    versionsData.push({
      name: data[i].drilldown.categories[j],
      y: data[i].drilldown.data[j],
      color: Highcharts.Color(data[i].color).brighten(brightness).get()
    });
  }
}

// Create the chart
Highcharts.chart('container2', {
  chart: {
    type: 'pie'
  },
  title: {
    text: 'Approved Tenure Mix'
  },
  subtitle: {
    text: 'Source: <a href="https://planbuild.southwark.gov.uk/documents/?casereference=16/AP/4458&system=DC" target="_blank">Southwark Council planning ref:16/AP/4458</a>'
  },
  plotOptions: {
    pie: {
      shadow: false,
      center: ['50%', '50%']
    }
  },
  tooltip: {
    valueSuffix: '%'
  },
  series: [{
    name: 'Policy Requirement',
    data: browserData,
    size: '60%',
    dataLabels: {
      formatter: function () {
        return this.y > 5 ? this.point.name : null;
      },
      color: '#ffffff',
      distance: -30
    }
  }, {
    name: 'Approved percentage',
    data: versionsData,
    size: '80%',
    innerSize: '60%',
    dataLabels: {
      formatter: function () {
        // display only if larger than 1
        return this.y > 1 ? '<b>' + this.point.name + ':</b> ' +
          this.y + '%' : null;
      }
    },
    id: 'versions'
  }],
  responsive: {
    rules: [{
      condition: {
        maxWidth: 400
      },
      chartOptions: {
        series: [{
          id: 'versions',
          dataLabels: {
            enabled: false
          }
        }]
      }
    }]
  }
});

</script>

Whether there will ever be even 116 social rent units is also open to doubt.  Leaving aside the fact that they won't be built for nearly ten years, a long time by any measure, Delancey has the option of passing the obligation to build the homes back to Southwark, along with land and _'sufficient funds'_ to fulfil the obligation.  We fear that the wording of the development's legal agreement fails to properly secure this. We also believe that the wording of the legal agreement fails to provide an effective viability review mechanism - a basic policy requirement and a way to get greater affordable and social rent housing, should the development prove more profitable than expected.

As well as housing, the new development will provide about the same amount of retail space as there is in the present shopping centre, but catering for the more well-heeled customer other social-rent free developments are now drawing to the Elephant.  The shopping centre itself will be demolished, which will destroy not just the shops of the many independent traders who have made the Elephant their home, including many ethnic businesses, but one of two major social hubs for the Latin American community in London (the other, in [Seven Sisters](https://www.facebook.com/wardscornercommunity/), is under similar threat). 

![](https://35percent.org/img/traderscomp.jpeg)

Concerted campaigning has gained some space for these traders in the shopping centre and other new developments, as well as a [temporary relocation facility](https://35percent.org/2018-11-24-castle-square-delancey-responds/), but there is not enough space for every trader who wants it.  [Latin Elephant](https://latinelephant.org/), a local charity and advocate for all ethnic traders in the area, reckons there are nearly a hundred independent traders in the area and, given the practicalities of moving a business and a limited relocation fund of [£634,700](https://planbuild.southwark.gov.uk/documents/?GetDocument=%7b%7b%7b!0iVzasdHCgb1eVmQCrssOg%3d%3d!%7d%7d%7d) only a fraction of traders are likely to benefit.

Delancey's anticipated profit from all of this is £137m or £148m, according to the last available [viability assessments](https://35percent.org/2018-07-02-viability-and-delancey/) and depending on the grant funding situation.  Delancey developments, at the Elephant, are based in [off-shore](https://35percent.org/2014-05-05-manx-connections-the-off-shore-home-of-the-elephants-developers/) tax-havens, with the shopping centre development registered in the British Virgin Islands.

![](https://35percent.org/img/delanceyshoppingcentrecgi.jpg)

## We must have homes that meet local need 
  
Delancey and Southwark argue that other elements of the scheme - a new Northern Line tube entrance and a campus for the University of the Art's London College of Communication - provide positives that [outweigh any negatives](https://35percent.org/shopping-centre) in the housing and retail offer.  This is entirely in keeping with the regeneration rationale, as articulated by Fred Manson back in 1999, so successfully implemented by Southwark since then and now making a sizeable contribution to London's disastrous housing situation - thousands of new homes that many, not just of the poorest, cannot afford to either rent or buy; housing costs for the poorest [the 'worst in Europe'](https://www.theguardian.com/society/2018/mar/21/uk-europe-housing-cost-rise-lowest-earners-report) and a [record number of rough sleepers](https://www.theguardian.com/society/2018/oct/31/record-number-of-people-are-sleeping-rough-in-london).

From the moment the shopping centre planning application was made [over two years ago](https://planbuild.southwark.gov.uk/documents/?GetDocument=%7b%7b%7b!qmb8aBDQpUlOrlnojZ2sVQ%3d%3d!%7d%7d%7d), Southwark Council has been content to take whatever Delancey has offered, regardless of local need, in pursuit of its wretched gentrification agenda.  It has been local campaigners, with the support of some local councillors, who have [fought hard](https://35percent.org/2018-12-16-mayor-approves-shopping-centre/) over the past two years to squeeze housing concessions and a better deal for shopping centre traders out of the development. We must now fully secure the maximum social rented housing, and not have to wait nearly ten years for them. 42 extra social rented homes are not that many, the London Mayor has the money to pay for them and we are determined that they should be built.  We also want a better deal for traders - more space and more money for relocating.

That is why we are challenging Delancey’s planning permission through the High Court.  We want the permission quashed and then we want a development scheme at the Elephant and Castle that provides homes and shops that are truly affordable for local people.

If you agree with us, you can help in this fight by donating [here](https://www.crowdjustice.com/case/stop-the-elephant-shopping-centre-destruction/) or coming to [support us at the High Court on Wednesday 17th July](https://twitter.com/UpTheElephant_/status/1144586245252759552).


__Footnotes:__

[^1]: Estates Gazzette article [published 13 March 1999](https://heygate.github.io/img/EstatesGazette.pdf)

<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@35percent_EAN">
<meta name="twitter:title" content="Why we are challenging the E&C redevelopment plans in court">
<meta name="twitter:description" content="Southwark Council - demolishing council homes, generating better people.">
<meta name="twitter:image" content="https://35percent.org/img/lovetheelephantbanner.jpg">

