# Exam 2 Study Guide

Exam 2 will be more conceptual than Exam 1. We are focusing on procedures for Vector an Raster analysis. I have posted my slides from our discussion of rasters. In particular, the section on interpolation was covered in lecture and is not covered in other materials.

Pay particular attention to:

* Bolstad Ch 9: Basic Spatial Analysis
* Bolstad Ch 10: Topics in Raster Analysis

## Vector Analysis

* Spatial query
* Spatial join
* Overlay analysis: intersect, clip, union etc.
* Other common geoprocessing tasks, such as dissolve, buffer, etc.

## Raster Model

* The resolution vs. storage tradeoff
* Raster compression methods

## Raster Analysis

* Types of interpolation: Inverse-distance weighting (IDW), Trend, Spline, Kriging. Understand how we classify analysis methods:
    * Exact vs appromimate
    * Local vs global
* Local, focal, and zonal analysis
* Various raster analysis functions: resampling, reclassification, etc. Be able to apply a reclassification table to a (small) input raster.
* Map algebra. Be able to apply a simple mathematical operation (such as addition) to two (small) input rasters.
* The purpose of various terrain analyses (slope, aspect, hillshade)
* Least-cost path calculation

## Example Questions

Example question: You would like to analyze the influence of socioeconomic characteristics on crime rates in New York City. Unfortunately, the crime data are only available by police precinct, while socioeconomic data is available by community district. What geoprocessing operation would create a new dataset that (a) has all attribute data from both the crime and socioeconomic dataset, and (b) creates a new set of geographic features formed by the overlapping borders of the police precincts and the community districts?

Example question: In a hypothetical scenario, a developer has decided to pursue transit oriented development (TOD) for new housing near Temple University. You've been asked to use vector operations to find a suitable location for this housing development based on the following criteria:

* The area should be located on residential land
* The area should be within 800 meters (a half mile) of a school
* The area should be within 500 meters of a SEPTA stop

Draw a flow chart that indicates the steps you would take for this site selection. Your cartographic model should detail each input, operation, output, and any relevant parameters.

Example question: Which interpolation method calculates a value at each point on the surface by averaging known (measured or sample) locations within a given distance (e.g., within 500 meters).

Example question: What is the purpose of zonal statistics in raster GIS? Use an example to support your answer.

Example question: Given two simple polygon layers, draw the resulting intersection layer. Show which attributes appear in the resulting layer.

