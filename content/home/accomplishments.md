---
# An instance of the Accomplishments widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Grants & Awards'
subtitle:

# Date format
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
  - date_start: '2021-06-29'
    description: Awarded to enable performance tests on GPU for the paper [Text Classification with Born's Rule]({{< relref "/publication/text-classification-with-born-rule" >}})
    organization: Google Cloud
    organization_url: https://cloud.google.com
    title: Google Cloud Research Credits
    url: 'https://edu.google.com/programs/credits/research/'
  - date_start: '2020-12-14'
    description: Awarded to support the maintainance of [COVID-19 Data Hub]({{< relref "/project/covid19" >}})
    organization: R Consortium
    organization_url: https://www.r-consortium.org
    title: R Consortium ISC Grant Program
    url: https://www.r-consortium.org/all-projects/call-for-proposals
  - date_start: '2020-04-28'
    description: Awarded to support the development of [COVID-19 Data Hub]({{< relref "/project/covid19" >}})
    organization: IVADO
    organization_url: https://ivado.ca/en/
    title: Institute for Data Valorization
    url: 'https://ivado.ca/en/scholarships-and-grants/covid-19-ivado-projects-and-initiatives/'

design:
  columns: '2'
---
