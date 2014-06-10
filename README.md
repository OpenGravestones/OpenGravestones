# Open-Gravestones

Open Gravestones is an open source project that will provide public domain cemetery and burial data that is based on open standards such as [GeoJSON-LD](https://github.com/geojson/geojson-ld) and [Schema.org](http://schema.org/) structured data.

Exisiting data schema:
* https://github.com/geojson/geojson-ld
* http://historical-data.org/Person.html
* http://schema.org/Cemetery
* http://rdf.muninn-project.org/ontologies/graves.html

Each cemetery listing should be encoded with the following [Schema.org](http://schema.org/Cemetery) `Cemetery` markup:

    <div itemscope itemtype="http://schema.org/Type" itemid="http://schema.org/Cemetery">
        <link itemprop="subClassOf" href="http://schema.org/CivicStructure"/>
        Address:
        <div itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
          <span itemprop="name">Arlington National Cemetery</span>
          <span itemprop="streetAddress">1 Memorial Drive</span>
          <span itemprop="addressLocality">Fort Myer</span>,
          <span itemprop="addressRegion">VA</span>
          <span itemprop="postalCode">22211</span>
        </div>
        Hours: <meta itemprop="openingHours" content="Mo-Su 08:00-17:00">Mon-Sun  8am – 5pm
        Phone: <span itemprop="telephone">877-907-8585</span>
        Website: <a itemprop="url" href="http://www.arlingtoncemetery.mil/">http://www.arlingtoncemetery.mil/</a>
    </div>
    
## Get involved!
* [Add to our research doc](https://docs.google.com/document/d/1dhvmF-WGlqp2T7OU27QM6LRcNdAsJhHzY3_-gW35py0/)


## Resources

### Metadata
* Will most likely utilize something like [Places](https://github.com/DallanQ/Places) or [GeoName](http://www.geonames.org/) for resolving place name queries.
* [How to mark up your content using microdata (Schema.org)](http://schema.org/docs/gs.html#microdata_how)
