# Open-Gravestones

Open Gravestones is an open source project that will provide public domain burial data that is based on open standards.

Exisiting data schema:
* http://historical-data.org/Person.html
* http://schema.org/Cemetery

See also:
* http://historical-data.org/

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

## Resources

### Metadata
* Will most likely utilize [Places](https://github.com/DallanQ/Places) for resolving place name queries.
* [How to mark up your content using microdata](http://schema.org/docs/gs.html#microdata_how)

## Get involved!
* [Add to our research doc](https://docs.google.com/document/d/1dhvmF-WGlqp2T7OU27QM6LRcNdAsJhHzY3_-gW35py0/)
