================================================================================
 THINGS I WOULD LIKE TO DO WITH THIS MOD IN THE FUTURE BUT CANNOT RIGHT NOW FOR
                   WHATEVER REASON (USUALLY INCOMPETENCE)
================================================================================

- Some better way of defining sounds for textures. The current sea of copy-paste
  is a pain in the ass. Some sort of new lump for applying things all nice-like
  ala Nashgore or Dmgnums would be a far better method, but I like the code-fu
  to write such things myself (never did get the hang of file i/o, sorry)
  
- Optimisation optimisations. The current method of deleting actors too close
  together works and results in good framerates, but can result in long load
  times, likely on account of CountProximity() being slow or something.
  
- Applying Soundsequences to sectors based on line textures, so that wooden
  doors actually sound like wooden doors instead of whirring sci-fi pistons.