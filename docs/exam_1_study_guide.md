# Exam 1 Study Guide

## Basic Concepts

Concepts to understand:

* The difference between the vector and raster model.
* Simple versus multi* geometries
* Topology
* Continuous vs. discrete data
* Scale, and various ways of expressing it
* Different kinds of generalization

Example question: What is GIS?

Example question: What are the three different types of vector geometries?

Example question: At a scale of 1 centimeter = 10 kilometers, what is the representative fraction?

Example question: What data model would be most appropriate for soil quality data?

Example question: In vector data, what distinguishes the topological model from the spaghetti model?

## Projections and Coordinate System

Concepts to understand:

* The difference between the geoid and the ellipsoid
* The datum
* Components of the latitude and longitude system (equator, graticule, etc.)
* Classification of projections (conformality, equivalence, etc.). What spatial property does each preserve?
* Common projections (Mercator, Robinson, etc.), their classification and typical use.
* Other coordinate systems (UTM, State Plane)

Example question: Given a picture of a globe, identify major elements of its coordinate system.

Example question: What two projections are used for all State Plane Zones outside of Alaska?

## Thematic Mapping/Map Design

Concepts to understand:

* The difference between reference maps and thematic maps
* Scales (or levels) of measurement (nominal, ordinal, interval, ratio)
* Qualitative vs quantitative data
* The various ways of visualizing data (choropleth maps, isarithms, dot density, etc.) and what each would be used for
* The elements of a map (legend, scale bar, etc.)
* Principles of classification (quantile, equal interval, natural breaks, etc.)
* Principles of map design
* Cartographic generalization

Example question: You have a dataset of real estate parcels with two attributes, the property class (residential, industrial, etc.) and the assessed value (estimated sale price). What scale of measurement is each attribute? What type of symbology would you use to visually represent each attribute?

Example question: You want to visualize population change between the 2010 and 2020 Census. Should you use a sequential, diverging, or qualitative color scheme?

You may be given the distribution of values in a field (e.g., fatalities per 100 million Vehicle Miles Travelled) as a table or as a histogram, and asked what classification method is appropriate.

You may also be given an example map and asked to identify poor design choices and errors.

## Databases

Concepts to understand:

* Meaning of tables, fields, records
* Attribute joins
* Common data types
* Primary keys (or key fields)
* Normalization
* Attribute query

Example question: Why do we normalize data in a relational database?

You may be given a set of tables and asked to put them into third (therefore second and first) normal form.

As in lecture, you may be given a table and asked which records (table rows) satisfy the search criteria given in a SQL `WHERE` clause (e.g. `WHERE age > 50 AND sex = 'female'`)

Conversely, you may be given the criteria in common language (find all females older than 50) and asked to write the SQL `WHERE` clause.

