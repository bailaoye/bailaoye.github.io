---
layout: post
title:      "CLI Portfolio Project"
date:       2020-06-27 08:07:26 +0000
permalink:  cli_portfolio_project
---


With the competion of the CLI project, we've now completed the first module (Ruby) of the software engineering course. 

Since the project was mostly self-driven, with no support from AAQ or guidance from tests like our previous work, taking the first steps to get started with my CLI were quite challenging. In fact, just getting the gem set up properly without breaking something in the sequence of generating the file structure took me a while to figure out! At the same time however, this has been by far the most I've learned in a single assignment at Flatiron and I look forward to further learning experiences that really push us out of our comfort zones.

Given my recent flight training, I decided to have my CLI project be in a related topic. As weather is a major determinant of whether flying can proceed or not on a given day for light aircraft, I wanted to create a CLI that could grab weather information in an aviation-specific format (the METAR), and present it in a human readable format.

The CLI got off to a rocky start, as I was quickly able to put together a simple scraper that grabbed data from the National Oceanic and Atmospheric Administration (NOAA) and presented it to the user. The app had the distinct advantage of being able to accept any airport code from any airport worldwide, but it did not generate its own objects, as outlined in the requirements. As such, my cohort lead pointed me towards a top-30 list of airports by passengers handled, and I spent the next while refactoring my code to both preserve the scraper code previously written and to split off a new Airport class to encapsulate these objects. 

With that, I'm happy to report that the CLI is now fully functional. While I haven't quite gotten around to refactoring it to be able to still search for any airport in the world (as opposed to only the top 30), the project now meets all requirements.

-J
