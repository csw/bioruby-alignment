# bio-alignment

Alignment handler for multiple sequence alignments (MSA).

This alignment handler makes no assumptions about the underlying
sequence object.  Support for any nucleotide, amino acid and codon
sequences that are lists. Any list with payload can be used (e.g.
nucleotide quality score, codon annotation). The only requirement is
that the list is iterable and can be indexed. 

This work is based on Pjotr's experience designing the BioScala
Alignment handler and BioRuby's PAML support. See also the
[design document]()

Note: this software is under active development.

## Developers

To use the library

```ruby
  require 'bio-alignment'
```

for code examples see ./spec/*.rb

## Cite

  If you use this software, please cite

    http://dx.doi.org/10.1093/bioinformatics/btq475

## Copyright

Copyright (c) 2012 Pjotr Prins. See LICENSE.txt for further details.

## Biogems.info

This exciting Ruby Biogem is published on http://biogems.info/