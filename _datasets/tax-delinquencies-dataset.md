---
schema: default
title: Property Tax Delinquencies Data
organization: City of Philadelphia - Revenue Department
notes: This is a dataset that shows the Philadelphia properties with tax delinquencies, including those that are in payment agreements.
resources:
  - name: Property Tax Delinquencies (CSV)
    url: 'https://phl.carto.com/api/v2/sql?q=SELECT+%2A+FROM+real_estate_tax_delinquencies&filename=real_estate_tax_delinquencies&format=csv&skipfields=cartodb_id,the_geom,the_geom_webmercator'
    format: csv
  - name: Property Tax Delinquencies (SHP)
    url: 'https://phl.carto.com/api/v2/sql?q=SELECT+%2A+FROM+real_estate_tax_delinquencies&filename=real_estate_tax_delinquencies&format=shp&skipfields=cartodb_id'
    format: zip
  - name: Property Tax Delinquencies (GeoJSON)
    url: 'https://phl.carto.com/api/v2/sql?q=SELECT+%2A+FROM+real_estate_tax_delinquencies&filename=real_estate_tax_delinquencies&format=geojson&skipfields=cartodb_id'
    format: geoJSON
  - name: Property Tax Delinquencies (API)
    url: 'https://cityofphiladelphia.github.io/carto-api-explorer/#real_estate_tax_delinquencies'
    format: api
  - name: Property Tax Delinquencies (Visualizations)
    url: 'https://data.phila.gov/visualizations/real-estate-tax-delinquencies'
    format: html
  - name: Property Tax Delinquencies (Metadata)
    url: 'http://metadata.phila.gov/#home/datasetdetails/57d9643afab162fe2708224e/representationdetails/57d9643cfab162fe27082252/'
    format: html
license: 'Other (City of Philadelphia)'
category:
  - Real Estate/Land Records
maintainer: Darshan Sumant
maintainer_email: darshansumant@uchicago.edu
---
