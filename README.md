Open-Gravestones
================

an open source cemetery CMS built on open standards

Exisiting data schema:
* http://schema.org/Person
* http://schema.org/Place
* http://schema.org/Cemetery
* http://historical-data.org/

Each cemetery listing should be encoded with the following Schema.org markup:

<code>
<div itemscope itemtype="http://schema.org/Type" itemid="http://schema.org/Cemetery">
   <link itemprop="subClassOf" href="http://schema.org/CivicStructure"/>
</div>
</code>

Get involved!
* Research doc: https://docs.google.com/document/d/1dhvmF-WGlqp2T7OU27QM6LRcNdAsJhHzY3_-gW35py0/
