---
# Please do not edit this file directly; it is auto generated.
# Instead, please edit 04-Using-interactive-elements.md in _episodes_rmd/
title: Using interactive elements
teaching: 45
exercises: 30
questions:
- "How do I use `shiny` in R Markdown documents?"
- "How can I share `shiny` apps?"
objectives:
- "To create interactive documents"
- "To understand how to host interactive applications"
keypoints:
- "`runtime: shiny` in the R Markdown header will enable using `shiny` components"
- "You do not need to worry about the ui.r file in this case"
- "You need a computer running R as the server to share `shiny` apps"
source: Rmd
---



How can I get the most out of interactivity before having to dive in and learn a lot?

##Interactivity for cheap

Use plotly::ggplotly() and renderPlotly()

# Shiny in Rmd docs

runtime: shiny

Don't need all the ui/server infrastructure. Rmd provides the ui, and output$XXXX gets managed for you just using the renderXXXX functions

Still have to give inputs an id and refer to them with input$XXXX



## How to host

shinyapps.io

Shiny.it.csiro.au

DIY?