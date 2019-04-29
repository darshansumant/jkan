---
schema: default
title: Property Assessments Data
organization: City of Philadelphia - Office of Property Assessment
notes: Property characteristic and assessment information from the Office of Property Assessment. Updated twice per week.
resources:
  - name: Property Assessments (CSV)
    url: 'https://phl.carto.com/api/v2/sql?q=SELECT+%2A,+ST_Y%28the_geom%29+AS+lat,+ST_X%28the_geom%29+AS+lng+FROM+opa_properties_public&filename=opa_properties_public&format=csv&skipfields=cartodb_id,the_geom,the_geom_webmercator'
    format: csv
  - name: Property Assessments (SHP)
    url: 'https://phl.carto.com/api/v2/sql?q=SELECT+%2A+FROM+opa_properties_public&filename=opa_properties_public&format=shp&skipfields=cartodb_id'
    format: zip
  - name: Property Assessments (GeoJSON)
    url: 'https://phl.carto.com/api/v2/sql?q=SELECT+%2A+FROM+opa_properties_public&filename=opa_properties_public&format=geojson&skipfields=cartodb_id'
    format: geoJSON
  - name: Property Assessments (API)
    url: 'https://cityofphiladelphia.github.io/carto-api-explorer/#opa_properties_public'
    format: api
  - name: Property Assessments (Visualizations)
    url: 'https://data.phila.gov/visualizations/property-assessments'
    format: html
  - name: Property Assessments (Metadata)
    url: 'http://metadata.phila.gov/#home/datasetdetails/5543865f20583086178c4ee5/'
    format: html
license: 'Other (City of Philadelphia)'
category:
  - Real Estate/Land Records
maintainer: Darshan Sumant
maintainer_email: darshansumant@uchicago.edu
---
