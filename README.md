# MBA-IT

## Pokyny pro vypracování postupové práce

* V rámci úvodu je nutné jasně stanovit cíle práce a návaznost jednotlivých kapitol;
* Teoretická část práce je založena zejména na rešerši provedené s využitím zdrojů uvedených v seznamu použité literatury;
* Analytická část práce spočívá v analýze, nikoliv v podrobném rozpracování teoretického konceptu, představeného v teoretické části;
* Analýza je založena na praktické implementaci / benchmarku metod popsaných v teoretické části (kriticky hodnotí reálnou / předpokládanou implementaci);
* Každý pojem musí být vysvětlen / definován při svém prvním použití;
* Všechny zdroje uvedené v seznamu použité literatury musí být citovány v textu;
* Citovat je nutné vždy původní zdroje (s případným odkazem na kontext v sekundárních citacích);
* Wikipedia není vhodný zdroj pro postupovou práci (s výjimkou vysvětlení pojmů a zkratek);
* Závěr práce se vyjadřuje k míře splnění definovaných cílů a shrnuje zásadní poznatky;
* Při citaci zdrojů je nutné dodržovat citační normu ISO-690. Doporučenou formou odkazů je Harwardský styl.

## Témata postupových prací Data/Information Management

### Možnosti využití dat jednotlivých vertikálách s ohledem na jejich kvalitu;
* Popis dané vertikály (finance, telco, retail, farmacie, ...);
* Popis užití dat v rámci vertikály (matice užití);
* Popis byznys dopadu nekvalitních dat podle jednotlivých vlastností dat.

### Data vs. Information Management
* Jaký je rozdíl mezi daty a informacemi?
* Jaký je potom rozdíl mezi Data a Information Management?
* Patří Business Intelligence do Data Management?
* Co je to Data Product? Existuje také Information Product?
* Jak souvisí kvalita dat s kvalitou informací?

### Microservices vs. SOA
* Jaké jsou principy Servisně Orientované Architektury?
* V čem se liší (a naopak neliší) Microservices a SOA?
* Kriticky zhodnoťte výhody a nevýhody obou přístupů;
* Uveďte příklady řešení, kdy je vhodnější použít SOA a kdy Microservices.

### Datové aktivum vs. produkt
* Co je to datové aktivum (asset) a jak souvisí s Data Governance;
* Co je datový produkt, jak souvisí s Data Mesh;
* Jaké jsou charakteristiky datových produktů a aktiv;
* Je skutečně datový produkt vhodnějším pojmem než datové aktivum?

### Důležitost řízení metadat v moderním řízení firmy
* Co jsou to metadata a jakým způsobem je lze členit;
* Jak souvisí metadata s hlavními historickými problémy Data Management;
* Co je to Data Liquidity/Interoperability a jak souvisí s řízením metadat;
* Představte příklady řešení, která jsou kriticky závislá na existenci metadat (HDFS, MDM, Data Virtualization, Data Lake, ...)
* Navhrněte implementaci metadata repository v rámci Vaší organizace;
* Zhodnoťte přínosy/náklady takové implementace.

### Master Data Management – porovnání přínosů a nákladů 
* Co je to Master Data Management;
* Jaký je rozdíl mezi řízením kmenových (master) dat a řízení referenčních dat?
* Relevantní entity pro MDM, specifické formy MDM;
* Návaznost MDM na Data Governance;
* Kritické zhodnocení přínosů;
* Kritické zhodnocení výše nákladů na implementaci a provoz;
* Kritické faktory úspěšnosti implementace MDM.

### Návrh přístupu k auditu datové kvality
* Co by měl obsahovat audit datové kvality;
* Jaké kroky existujících metodik pro řízení kvality dat odpovídají auditu kvality;
* Jaká by měla být vazba auditu datové kvality na audit informačního systému?
* Jaké standardy lze použít pro audit kvality dat;
* Navrhněte plán auditu.

### Dopad metrik výkonnosti řízení dat do metrik výkonnosti ostatních oblastí řízení IT/firmy
* Řízení dat jako jedna z dimenzí řízení informatiky;
* Metriky výkonnosti informatiky;
* Metriky výkonnosti řízení dat;
* Kauzální závislosti mezi metrikami výkonnosti.

### Význam online datové kvality
* V čem je specifické řízení kvality dat majících charakter streamu?
* Popište význam a architekturu DQ Firewall;
* Jakým způsobem byste implementovali DQ Firewall;
* Jakým způsobem byste v takovém případě řešili dávkové (batch) loady dat?

### Porovnání míry dopadu nekvalitních dat ve státním a soukromém sektoru
* Formy užití dat ve státním a soukromém sektoru;
* Náklady nekvalitních dat ve státním sektoru;
* Náklady nekvalitních dat v soukromém sektoru;
* Srovnání míry dopadu v rámci obou sektorů.

### Metody pro deduplikaci a unifikaci
* Popis problematiky duplicitních dat;
* Popis technik pro vypořádání se s duplicitními daty;
* Popis možných úskalí deduplikace a unifikace dat.

### Kritické faktory úspěšnosti nasazení Data Lake v organizaci
* Co je to Data Lake a jaké jsou rozdíly oproti klasickému Datovému Skladu;
* Jaké jsou možnosti začlenění Data Lake do IS (výstup: schéma možností);
* Jaké jsou možnosti použitých technologií (výstup: srovnání možností);
* Jaká jsou možná rizika (výstup: analýza rizik);
* Na základě analýzy formulujte kritické faktory úspěšnosti (výstup: strukturovaný přehled faktorů úspěšnosti s vyznačením kritických faktorů s odůvodněním).

### Data Lake s využitím on-prem HDFS a on-cloud Object Storage
* Co je to Data Lake a jaké jsou rozdíly oproti klasickému Datovému Skladu;
* Co je HDFS, Object Storage – výhody / nevýhody z pohledu technologií;
* Nákladové implikace on-prem / on-cloud;
* Budoucí vývoj.

### Kritické zhodnocení Data Mash jako datové architektury budoucnosti
* Monolytická vs. Distribuovaná datová architektura;
* Hlavní principy Data Mash;
* Jaká jsou negativa / positiva (úskalí).

### Vliv datové kvality na získávání znalostí z databází
* Jaký mají vlastnosti dat vliv na kvalitu modelů?
* Jaké vlastnosti mají největší vliv?
* Jak lze tomuto negativnímu jevu čelit?

### Data Sustainability
* Jaký je dopad zpracování dat na životní prostředí?
* Porovnejte on-premise a in-cloud jako alternativy.

### Kritické zhodnocení přínosů Feature Store
* Co je to Feature Store a jaký je rozdíl oproti analytickému data martu?
* Pro jaké typy pokročilé analýzy (deskriptivní, prediktivní, preskriptivní, ...) lze Feature Store použít?
* Do jaké míry lze očekávat znovupoužitelné features a do jaké míry jsou specifické pro konkrétní model?
* Navrhněte datovou a aplikační architekturu Feature Store.

## Témata postupových prací Knowledge Management/Engineering

### Etické aspekty expertních systémů
* Role experta a znalostního inženýra;
* Kde leží odpovědnost za selhání systému?

### Návrh expertního systému
* Návrh konkrétního řešení expertního systému v oblasti jíž se zabýváte;
* Zhodnocení přínosů a možných úskalí;
* Vymezení kritických faktorů úspěšnosti implementace.

###  Úskalí získávání znalostí z textových dokumentů
* Stručně charaktrizujte problematiku získávání znalostí z textů;
* K jakému účelu je možné techniky získávání znalostí z textů použít?
* S jakými úskalími se lze setkat?
* Jakým způsobem se s nimi lze vypořádat?

### Trendy v oblasti znalostního managementu
* Jaké jsou nejčastější současné úlohy v rámci znalostního managementu?
* Kriticky zhodnoťte trendy v této oblasti;
* Jaký bude podle Vás další vývoj znalostního managementu?

### Kritické faktory úspěšnosti zavedení znalostního managementu
* Jaké znáte kritické faktory úspěšnosti implementace znalostního managementu?
* Přiřaďte tyto kritické faktory k jednotlivým fázím životního cyklu implementace řešení z oblasti znalostního managementu;
* Popište jednotlivé KF: popis faktoru, související hrozby, návrh jejich řešení.

### Trendy a výzvy v oblasti získávání znalostí z databází /textů/audia/videa ...
* Jaké znáte trendy v této oblasti? 
* Kriticky zhodnoťte tyto trendy?
* Jaký bude podle Vás další vývoj?

### Možnosti využití znalostí v dané vertikále (E-business, Finance, Retail, Telco,...)
* Jaké vidíte možnosti využití získaných znalostí pro danou vertikálu?
* S jakými úskalími je využití znalostí pro tyto účely spojeno?
* Detailně popište vybraný způsob využití.

### Možnosti využití znalostí pro CRM
* Jaké vidíte možnosti využití získaných znalostí pro CRM?
* S jakými úskalími je využití znalostí pro tyto účely spojeno?
* Detailně popište vybraný způsob využití.

### Implementace znalostního managementu – projekt nebo kontinuální vývoj?
* Zamyslete se nad uvedenými variantami implementace znalostního managementu;
* Kriticky zhodnoťte přínosy / nevýhody obou přístupů.

### Možnosti využití inteligentních agentů
* Jaké jsou typy inteligentních agentů;
* Zamyslete se nad možnostmi využití inteligentních agentů;
* Popište konkrétní praktický příklad jejich využití.

### Možnosti využití sociálních sítí a groupware aplikací pro Knowledge Management
* Popište hlavní problémy znalostního managementu;
* Jakým způsobem mohou při řešení těchto problémů pomoci sociální sítě a groupware aplikace?
* S jakými úskalími je spojena jejich implementace?
* Navrhněte implementaci v prostředí Vaší organizace.