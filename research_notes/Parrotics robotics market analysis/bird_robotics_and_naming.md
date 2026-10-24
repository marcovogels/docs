# Bird-inspired robotics and the "Parrotics" naming/trademark landscape (as of 2026-10-24)

Scope note: These notes come from about 20 web searches and fetches run on 2026-10-24. Two primary sites could not be reached from the research environment (flapper-drones.com and robotsguide.com both failed DNS lookup). GitHub-wide search was also blocked (the session is limited to its configured repositories). I did not query the trademark databases (EUIPO eSearch, USPTO, WIPO Global Brand Database) directly, so every trademark statement below is a risk flag or a recommended method. None of it is a clearance result or a legal conclusion.

## Research state of the art: perching, flapping-wing, legged/climbing and gripper robots

### Takeaway
Bird-inspired robotics is still mostly lab-stage (roughly TRL 3–6). The main recent results are Stanford's SNAG perching gripper (2021), EPFL's RAVEN jumping/walking drone (Nature, Dec 2024), Harvard's RoboBee landing legs (Science Robotics, Apr 2025) and a 2025 review of perching on flapping-wing robots. Festo's birds are technology showcases, not products. Flapping-wing platforms are getting good at indoor flight and early perching, but flight times are only minutes.

### Cited Findings
**Perching drones**
- Stanford's SNAG ("stereotyped nature-inspired aerial grasper") is a bird-claw gripper mounted on a quadcopter. It can fly, catch and carry objects, and perch on varied surfaces. Its leg is modelled on a peregrine falcon, it clutches in about 20 ms, and it was tested in Oregon forests. It was published in December 2021, so it is now nearly five years old. — [Stanford News](https://news.stanford.edu/?p=41966); [ScienceDaily, Dec 2021](https://www.sciencedaily.com/releases/2021/12/211201145322.htm)
- A *Biomimetics* review from October 2025 covers bio-inspired perching mechanisms for flapping-wing robots. It sorts the work into mostly large-scale systems (>100 g) and some small-scale ones (1–100 g). — [PMC review, 2025](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12561895/)
- A 2024 arXiv paper demonstrates "repeatable energy-efficient perching for flapping-wing robots using soft grippers." — [arXiv 2409.11921](https://arxiv.org/pdf/2409.11921)
- A University of Tokyo team adapted a Flapper Nimble+ for falconry-style landing on a human hand. It followed the planned path with an RMS error of 0.1695 m. — [TechEBlog](https://www.techeblog.com/university-of-tokyo-flapping-wing-drone/)
- Older academic work includes a bird-inspired foot/limb study for perching drones (tendons, toe pads) — [HAL](https://hal.archives-ouvertes.fr/hal-03103963)

**Legged / multimodal (EPFL RAVEN)**
- RAVEN ("Robotic Avian-inspired Vehicle for multiple ENvironments") was published as "Fast ground-to-air transition with avian-inspired multifunctional legs" in *Nature* 636, 86–91 (2024), by Won Dong Shin, Hoang-Vu Phan, Monica Daley et al. (EPFL with UC Irvine). EPFL announced it on 6 Dec 2024. — [EPFL news](https://actu.epfl.ch/news/bird-inspired-drone-can-jump-for-take-off-4); [ScienceDaily](https://sciencedaily.com/releases/2024/12/241206111951.htm)
- Its crow/raven-inspired legs let it walk, cross gaps and jump onto a surface about 26 cm high. Jumping into flight made the best use of kinetic and potential energy compared with standing or falling take-offs. — [EPFL news](https://actu.epfl.ch/news/bird-inspired-drone-can-jump-for-take-off-4)
- It weighs 620 g and uses passive spring-like joints and flexible toes. It jumps about 0.5 m before the propeller accelerates it (about 2.2 m/s reported). These specs come from secondary coverage and should be checked against the paper. — [Digitec](https://www.digitec.ch/en/page/swiss-engineers-build-flying-robots-with-legs-35943)
- The researchers call it "a first step" toward understanding multimodal flying animals, which marks it as research-stage. — [EPFL AI Center](https://ai.epfl.ch/bird-inspired-drone-can-jump-for-take-off/)

**Flapping-wing / insect-scale**
- Festo SmartBird (2011) is gull-inspired, about 1.6x a herring gull's span at about one-third the weight. It takes off, flies and lands using only its wings and needs 23 W for propulsion. — [Lynceans (secondary)](https://lynceans.org/tag/festo/)
- Festo BionicSwift (2020) is 44.5 cm long, has a 68 cm wingspan, weighs 42 g, uses feather-like lamellae wings, and flies coordinated indoors using UWB "indoor GPS." Both Festo birds belong to the Bionic Learning Network as showcases, not products. I did not reach Festo's own pages, so figures are from secondary sources. — [SlashGear](https://www.slashgear.com/bionicswift-robotic-bird-has-artificial-feathers-03627604/bionicswift3-1/); [Lynceans](https://lynceans.org/tag/festo/)
- DelFly Nimble (TU Delft, 2018) was the first tailless DelFly. It steers by changing wing motion and can do 360° flips. Flapper Drones was spun off in 2019 to commercialise it. — [Wikipedia: DelFly](https://en.wikipedia.org/wiki/DelFly)
- Harvard RoboBee (Robert Wood's Microrobotics Lab) gained crane-fly-inspired jointed legs and a new decelerating controller (Science Robotics cover, Apr 2025). This protects its fragile piezo actuators. Previously the team "would turn off the vehicle a little bit above the ground and just drop it." — [Harvard SEAS, Apr 2025](https://seas.harvard.edu/news/2025/04/robobee-comes-landing); [Purdue ECE](https://engineering.purdue.edu/ECE/News/2025/purdue-professor-helps-tiny-robobee-learn-to-land-softly-thanks-to-lessons-from-nature); [The Robot Report](https://www.therobotreport.com/harvard-equips-robobee-crane-fly-inspired-landing-gear/)
- A 2026 follow-up article says RoboBee uses an optic-flow-like time-to-contact model to power off its wings before impact. — [Science Connected, Aug 2026](https://magazine.scienceconnected.org/2026/08/robobee-lands-softly-with-new-legs/)
- Ornithopter vision stabilisation ("artificial microsaccade compensation") is an active research topic. — [arXiv 2512.03995](https://arxiv.org/pdf/2512.03995)

**Parrot-like climbing / beak grippers**
- UTS (Sydney) ParCli ("PARrot-CLImbing robot") is a three-limbed climber whose large central limb copies a parrot's beak. It is aimed at climbing sparse structures such as power-transmission towers, and later at tool use (grinding, cutting, welding). It has 14 BLDC motors and a 6800 mAh battery, and weighs about 10.5 kg. — [UTS News, Oct 2023](https://www.uts.edu.au/news/2023/10/parrot-inspired-robot-aims-make-workplaces-safe); [Tech Briefs contest entry 2023](https://contest.techbriefs.com/2023/entries/robotics-and-automation/12239)
- ParCli is being taken forward by the startup Crest Robotics. I found no update after 2023. — [UTS TechLab](https://techlab.uts.edu.au/crest-robotics-climbing-robot/)
- Biology basis: in lovebirds the beak produces forces comparable to the hindlimbs, so the head works as a "third limb" when climbing. — [NYIT feature](https://nyit.edu/box/features/polly_want_to_climb)

### Inferences
- Perching (passive claw grippers, soft grippers) is the bird capability closest to transfer. It works on quadcopters (SNAG) and is now being shown on flapping-wing robots (2024–2025 papers). Long-duration perch-and-stare inspection or surveillance looks technically plausible but unproven in field products.
- Multimodal legged drones (RAVEN) and beak-limb climbers (ParCli) are TRL 3–5 prototypes. Startup timelines to product are likely years.
- Flapping-wing flight times are minutes (see Nimble+ below), so endurance is the main barrier for any flying bird robot outside entertainment.

### Gaps
- I found no reliable TRL ratings, unit costs or battery-life figures for SNAG, RAVEN or ParCli in primary sources.
- I did not reach Festo's primary pages to confirm specs or whether new bionic birds appeared in 2025–2026.
- No 2026 perching-drone product launches surfaced. That may be a search limitation, not evidence there are none.
- I did not research safety certification (e.g., EN 71 toy safety, drone category rules) for flapping robots.

## Commercial bird-inspired products: Robird, Flapper Nimble+, toys and companion robots

### Takeaway
Only a few bird-inspired robots are actually sold. Flapper Drones' Nimble+ is an indoor research/education/show platform priced at about US$2,200 (early-access software, on-demand stock). Robird is a falcon-shaped bird-deterrence drone run as a service, with documented airport seasons around 2016–2018. Its current commercial status could not be confirmed. I did not research toy ornithopters or talking-parrot and companion bird robots in this pass.

### Cited Findings
**Flapper Drones / Nimble+**
- The Nimble+ is a tailless flapping-wing drone for indoor research, education, demonstration shows and autonomy development. It works with Lighthouse, UWB and optical motion-capture positioning and supports swarms. — [Wevolver on X, 2025](https://x.com/WevolverApp/status/1957842591354876324); [Wevolver on X](https://x.com/WevolverApp/status/1968788689275814194)
- Hardware: about 114 g, about 49 cm long, wings flapping about 10–12 Hz, a Crazyflie Bolt 1.1 flight controller, and soft wings for safety and crash tolerance. It is open source. — [Hackster.io](https://www.hackster.io/news/flapper-drones-releases-its-latest-open-source-drone-the-flapper-nimble-0e743166b573); [Bitcraze blog](https://www.bitcraze.io/2022/07/flapper-drones-bioinspired-robots-powered-by-crazyflie-bolt/)
- Flight time: more than 5 minutes of hovering with a 25 g payload, per the manufacturer as cited in a paper. — [arXiv 2409.11921](https://arxiv.org/pdf/2409.11921)
- Price (Starter Kit): US$2,200 at RobotShop US and the Bitcraze store, £2,030.77 at RobotShop UK, C$3,142.86 at RobotShop CA and A$5,028.56 at Pakronics AU. Bitcraze lists it as "early access" (hardware tested, software work in progress). RobotShop marks it "On Demand," not normally stocked. — [RobotShop](https://www.robotshop.com/products/flapper-drones-flapper-nimble-starter-kit); [Bitcraze store](https://store.bitcraze.io/products/flapper-nimble-starter-kit); [Pakronics](https://pakronics.com.au/products/crazyflie-flapper-nimble-starter-kit-800000006)
- Company origin: a TU Delft spinoff founded in 2019. Coverage also describes it as Czech-based, building on TU Delft and ULB academic work. Sources are inconsistent, so check the company directly. — [Wikipedia: DelFly](https://en.wikipedia.org/wiki/DelFly); [Hackster.io](https://www.hackster.io/news/flapper-drones-releases-its-latest-open-source-drone-the-flapper-nimble-0e743166b573)

**Robird (Clear Flight Solutions, NL / Aerium Analytics, CA)**
- Robird is a remotely piloted robotic bird made to look and fly like a falcon to scare off birds. It comes from Clear Flight Solutions, a University of Twente spin-off. — [CORDIS project 868389](https://cordis.europa.eu/project/id/868389); [ASME](https://www.asme.org/topics-resources/content/flying-robirds-increase-safety-airports)
- Its first airport test site was Weeze Airport, Germany (2016). — [IMechE](https://www.imeche.org/news/news-article/robird-to-make-its-first-airport-flights)
- Aerium Analytics (Calgary) ran it at Edmonton International Airport from about 2017–2018, alongside lasers and sound effects. Limits: it cannot fly in rain or (under regulations) at night, and it is unlikely to be an airport's only bird-control method. — [The Engineer](https://theengineer.co.uk/content/news/edmonton-airport-establishes-routine-drone-usage-with-bird-scarer); [CBC](https://amp.cbc.ca/news/canada/edmonton/drone-bird-airport-uav-edmonton-international-airport-falcon-1.4168404); [Global News](https://globalnews.ca/news/3540654/robotic-falcon-takes-flight-at-edmonton-international-airport/amp/)
- A Dutch parliamentary document (undated) lists seasons at Edmonton, Grand Forks, Southampton and Zürich airports and more than 1,000 airport flights. — [OpenState PDF](https://llms.openstate.eu/docs/62/3c/623c3b30-153b-497c-8c6d-a716161495c3.pdf)
- Funding: about $2 M from the Cottonwood Euro Technology Fund (ASME, undated), and €1.6 M per Emerce. These may describe the same round. — [ASME](https://www.asme.org/engineering-topics/articles/robotics/flying-robirds-increase-safety-airports); [Emerce](https://www.emerce.nl/?p=549225)
- Aerium's website still lists RoBird for wildlife management (footer © 2025) but gives no new deployment details. — [Aerium Analytics](https://aeriumanalytics.com/tag/edmonton-international-airport/page/2)

### Inferences
- Bird deterrence is the clearest proven commercial niche for bird-shaped robots. It is sold as a piloted service, not hardware, and limited by weather, night rules and the need for a pilot. Its business traction after about 2019 is unclear, which a newcomer should investigate before treating it as a validated market.
- Indoor, soft-winged flapping drones are a real, if small and expensive (about $2k), niche in education, research and shows. A cheaper consumer or edutainment version would be a gap, but flight time is 5+ minutes.

### Gaps
- Robird / Clear Flight Solutions status in 2024–2026 (operating, acquired, wound down) is unconfirmed. I found no 2024–2026 news.
- I could not open the official Flapper Drones site to confirm the EUR price, current models or 2026 news.
- Not researched in this pass: toy ornithopters (e.g., hobby rubber-band and RC flapping birds), talking/mimicking parrot toys, and bird-shaped companion robots. Their sales figures are missing.
- I found no market-size data for bird-deterrence drones or flapping-wing drones.

## Naming and trademark landscape for "Parrotics" (plus Budgie, Macaw, Cockatoo)

### Takeaway
A web search found no company or product called "Parrotics". The only notable prior use is as a section title in Paul Carter's book *Parrot*. parrotics.com was registered on 2026-10-24 via Hostinger. The main risk is Parrot SA (Paris), an active, growing drone maker. Its house mark "Parrot" is fully contained in "Parrotics," and it trades in the same goods (drones, Nice class 9 and related). If Parrotics makes drones, likelihood-of-confusion risk looks material and needs a professional clearance search. Budgie and Macaw are already well-known software or tech names. I could not verify Cockatoo.

### Cited Findings
**Existing uses of "Parrotics"**
- Web search for "Parrotics" returned only Paul Carter's book *Parrot*, where "Parrotics" is the first of three sections (with "Parroternalia" and "Parrotology"). No company, product or brand use surfaced. — [University of Chicago Press](https://press.uchicago.edu/ucp/books/book/distributed/P/bo3534916.html); [Goodreads](https://www.goodreads.com/en/book/show/1182601.Parrot)
- parrotics.com: RDAP shows registration on 2026-10-24T16:28:57Z, expiry 2027-10-24, registrar Hostinger operations UAB, status "client transfer prohibited." The domain returned HTTP 200, probably a registrar placeholder (not inspected). — [Verisign RDAP](https://rdap.verisign.com/com/v1/domain/parrotics.com)

**Parrot SA (the main conflict risk)**
- Parrot SA is a French company in Paris. Since 2017 it has focused exclusively on drones (ANAFI line). — [Wikipedia: Parrot SA](https://en.wikipedia.org/wiki/Parrot_SA)
- It reported record 2025 revenue of €79.8 M (+6% at constant FX). Professional micro-UAVs (ANAFI UKR) brought in €47.9 M, with more than 4,000 premium ISR micro-UAVs sold. It also signed a multi-year contract with a new NATO country, and booked 2026 orders are close to full-year 2025 micro-drone revenue. Net loss was €14.5 M. — [Parrot Q4 2025 release](https://www.parrot.com/assets/s3fs-public/document/PARROT_CP_CA-T4-2025_20260220_EN_DEF.pdf); [MarketScreener](https://www.marketscreener.com/news/parrot-reports-record-2025-revenue-ce7e51d8d980f424); [Boursorama](https://www.boursorama.com/bourse/actualites/parrot-parrot-2025-fourth-quarter-business-02a5d18b79ea47178ad48fdb17840410)
- The ANAFI UKR replaced the ANAFI USA range in under 18 months. — [financialfilings.com](https://financialfilings.com/filings/parrot/earnings-release/2026/34550995/)
- Parrot (as PARROT DRONES) holds EU registrations for product marks such as ANAFI (EUTM 017838401) and ANAFI USA (EUTM 018217382). It has also filed others (e.g., SELF FLYER). This shows it actively files trademarks. — [TrademarkElite: ANAFI](https://www.trademarkelite.com/europe/trademark/trademark-detail/017838401/ANAFI); [TrademarkElite: ANAFI USA](https://www.trademarkelite.com/europe/trademark/trademark-detail/018217382/ANAFI-USA); [ParrotPilots forum](https://parrotpilots.com/threads/a-new-trade-mark-pending-by-parrot-self-flyer.4202/)
- Parrot's earlier consumer drone lines (AR.Drone, Bebop) put the "Parrot" brand on consumer drones and toys for years. — [Wikipedia: AR.Drone](https://en.wikipedia.org/wiki/Parrot_AR.Drone); [Wikipedia: Bebop](https://en.wikipedia.org/wiki/Parrot_Bebop)
- My search found no public record of Parrot opposing third-party marks at EUIPO. This is not evidence that none exist. — [Finnegan: Drones and IP (background)](https://www.finnegan.com/en/insights/articles/drones-and-ip-where-and-why-are-they-taking-off.html)

**Other bird names**
- **Budgie**: an established open-source Linux desktop environment (created by Ikey Doherty for Solus; ships as Ubuntu Budgie). It is a software/class 9 association. — [Wikipedia: Budgie](https://en.wikipedia.org/wiki/Budgie_(desktop_environment)); [OMG! Ubuntu](https://www.omgubuntu.co.uk/?p=89503)
- **Macaw**: a code-generating web design app (2013 Kickstarter), acquired by InVision in 2016 and since discontinued. Old marks may have lapsed, but the name still carries a known software association. — [TechCrunch](https://techcrunch.com/?p=1267716); [InVision blog](https://invisionapp.com/blog/macaw-team-joins-invision); [Crunchbase](https://www.crunchbase.com/organization/macaw)
- **Cockatoo**: my search found no notable tech product of that name. It is unverified.

**Search approach (method, not results)**
- Databases to check: EUIPO eSearch plus / TMview (EU and national offices, including INPI France, Parrot's home office), USPTO Trademark Search, and WIPO Global Brand Database (Madrid filings). Search the exact term "PARROTICS" and also "PARROT*" prefix and phonetic variants. I did not run these checks.
- Relevant Nice classes: 9 (drones with cameras, software, electronics), 12 (vehicles, including drones in some offices), 28 (toys, toy drones, games), 7 (robots for industrial use) and 42 (software/SaaS). Parrot's ANAFI registrations should be checked for exact class coverage.

### Inferences
- "Parrotics" contains the whole distinctive mark "Parrot" plus a descriptive-sounding suffix ("-otics" suggesting robotics). Examiners and opponents often compare dominant elements, so for drones and robotics goods the overlap with Parrot SA's mark and trade field looks like a high-risk area. It deserves a professional clearance search and attorney opinion before filing or launch (not a legal conclusion).
- Risk is likely lower if goods avoid drones/UAVs (e.g., non-flying grippers or climbing robots). But Parrot may claim a broad reputation in consumer electronics from its earlier products, so lower risk is not no risk.
- An EU/French conflict is probably most likely because Parrot is French and EU-active. US exposure also matters because of ANAFI USA and its US defense market.
- Budgie and Macaw would compete for search attention with established software names. Weak software marks in other classes may not block robotics goods, but that also needs checking.
- Recommendation: retain a trademark attorney (EU and US) to run a full clearance search across classes 7, 9, 12, 28 and 42 before investing in branding. Consider backup names that do not contain "Parrot."

### Gaps
- I did not query EUIPO, USPTO or WIPO directly, so I have no list of live "PARROT"-formative marks or their classes.
- GitHub search was blocked in this environment, and app stores and social handles (X, Instagram, LinkedIn, TikTok) were not checked for "Parrotics."
- I did not verify a "Cockatoo" tech product, or "Budgie"/"Macaw" registrations in robotics classes.
- I found no case law or opposition history involving Parrot SA's "Parrot" mark.

## Opportunities: what is close to commercial viability vs still research

### Takeaway
Nearest to market: indoor soft-wing flapping drones for education, research and shows (already sold at about $2k), and falcon-like bird deterrence as a service (deployed at airports, but traction since about 2019 is unclear). Mid-term: perching for persistent inspection or surveillance (good grippers exist, no proven product). Research-stage: multimodal walking/jumping drones, insect-scale flappers and parrot-style climbing robots.

### Cited Findings
- Indoor flapping drones are commercially available (Nimble+ at US$2,200, "early access" software), with soft wings marketed as safer and more crash-tolerant. — [Bitcraze store](https://store.bitcraze.io/products/flapper-nimble-starter-kit); [Hackster.io](https://www.hackster.io/news/flapper-drones-releases-its-latest-open-source-drone-the-flapper-nimble-0e743166b573)
- Bird deterrence works because birds are hard-wired to fear raptors, so they are thought less likely to get used to it. Real-world limits are weather, night and the need for a pilot. — [TechRadar](https://www.techradar.com/news/this-robot-bird-will-scare-real-birds-away-from-airports); [CBC](https://amp.cbc.ca/news/canada/edmonton/drone-bird-airport-uav-edmonton-international-airport-falcon-1.4168404)
- Perching grippers work on quadcopters in the field (SNAG, forest tests) and are emerging on flapping robots. — [Stanford News](https://news.stanford.edu/?p=41966); [arXiv 2409.11921](https://arxiv.org/pdf/2409.11921); [PMC review 2025](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12561895/)
- RAVEN is explicitly "a first step." RoboBee only gained reliable landing in 2025. ParCli is a proof of concept. — [EPFL](https://ai.epfl.ch/bird-inspired-drone-can-jump-for-take-off/); [Harvard SEAS](https://seas.harvard.edu/news/2025/04/robobee-comes-landing); [UTS](https://www.uts.edu.au/news/2023/10/parrot-inspired-robot-aims-make-workplaces-safe)
- Infrastructure climbing (power towers) is an articulated use case for parrot-style climbing robots. — [UTS TechLab](https://techlab.uts.edu.au/crest-robotics-climbing-robot/)

### Inferences
- A startup could win quickest with a cheaper, safer indoor bird-shaped flapper for education or entertainment (below the $2k Nimble+), or by adding SNAG-style perching to a quadcopter for perch-and-stare inspection, which saves battery.
- Bird deterrence has precedent but also a cautionary note: Robird's visibility seems to have faded after its 2016–2018 airport pilots, which suggests hard unit economics (pilot labour, weather limits).
- The flying bird-shaped segments (drones and deterrence) are also where the "Parrot" naming risk is highest.

### Gaps
- I found no market-size, revenue or unit-economics data for flapping drones, bird-deterrence services or perching drones.
- No evidence was found on regulatory treatment of flapping-wing drones versus multirotors (e.g., EASA/FAA categories, bird-protection law for deterrence).
- Consumer demand for bird-shaped companion or talking robots was not researched.
