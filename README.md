# Progress 

## SPH
**veskery kod v tomto repozitari** [sph-mountain-waves](https://github.com/moschehaus/sph-mountain-waves)
- [x] zavedeni adaptivni artificialni viskozity
- [x] zavedeni variabilni smoothing length
    - [x] zpresneni pomoci Newtona
- [x] pokus o alternativni formulaci (*pressure-entropy*) ala Hopkins
- [ ] pokus o well-balancovani SPH schematu
- [x] experimentovani s ruznymi formulacemi: perturbace skrze WCSPH, vse skrze Hopkinse,...
- [x] monitorovani energie a obecne vylepseni diagnostiky
- [x] prepis *multi-mass distribution* na *single-mass distribution*
- [x] prechod k exponencialnimu pocatecnimu rozdeleni
- [x] implementace okrajovych podminek:
    - [x] zkvalitneni hranice
    - [x] dolni podminka: *noslip* ci *freeslip*?
    - [x] vtok: 
    - [x] vytok: periodicke?
    - [x] horni podminka: Rayleigh?

### Formulace
- **klasicke WCPSH**: plna formulace, diskretizace rovnice kontinuity
- **well balanced WCPSH**: stepeni na pozadi + perturbaci, diskretizace rovnice kontinuity
- **klasicky Hopkins**: plna formulace, adaptivni delka
- **: well balanced Hopkins*: $a' = a - a_0,$ adaptivni delka
***
- **WCSPH Hopkins**?: advekce entropie, ale interakce dle WCSPH
- **θ-Hopknis**?: Hopkinsova entropy-like variable $A$ by melo byt mozne vyjadrit pomoci potencialove teploty θ, ktera se ma taky zachovovat

## Lagrangian Voronoi

# AI acknowledgment

AI writing and language tools — specifically Writefull and Claude (Anthropic) — were used for auxiliary tasks including proofreading, prose checking, and code and TeX debugging, as well as for the preparation of figures in Makie.jl and TikZ. All scientific content, numerical implementations, and analytical conclusions are the author's own work.
