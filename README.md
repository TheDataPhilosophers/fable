# fable
System Administrator Assistant

Within the last few decades, the era of computers grew without leaps and bounds, cutting down the cost of computing. But with such a radical growth, too many varied technologies sprouted, to ease the life of application developers and to meet the needs of users with minimal turn around time. Mastering every one of these technologies isn't an easy task and finding developers proficient in a multitude of technologies is also a cumbersome task, not to mention if the technology is anew or grew to be obsolete. With every technology employed in a firm, arises the need for administrators who are primarily responsible for the upkeep and safeguard of these essential building blocks. The day-to-day tasks performed by these administrators are crucial for any firm to make sure their services and transactions are uninterrupted.

Below is [Wikipedia's](https://en.wikipedia.org/wiki/System_administrator#Related_fields) classification of the system administrator into multiple roles depending on the type of technology they deal with.
1. A **database administrator (DBA)** maintains a *database system* and is responsible for the integrity of the data and the efficiency and performance of the system.
2. A **network administrator** maintains *network infrastructure* such as switches and routers and diagnoses problems with these or with the behaviour of network-attached computers.
3. A **security administrator** is a specialist in *computer and network security*, including the administration of security devices such as firewalls, as well as consulting on general security measures.
4. A **web administrator** maintains *web server services* (such as Apache or IIS) that allow for internal or external access to web sites. Tasks include managing multiple sites, administering security, and configuring necessary components and software. Responsibilities may also include software change management.
5. A **computer operator** performs *routine maintenance and upkeep*, such as changing backup tapes or replacing failed drives in a redundant array of independent disks (RAID). Such tasks usually require a physical presence in the room with the computer, and while less skilled than sysadmin tasks, may require a similar level of trust since the operator has access to possibly sensitive data.
6. An **SRE (Site Reliability Engineering)** - takes a software engineering or programmatic approach to managing systems, one of the emerging and promising discipline, aimed to reduce the number of effort developers put into the operations.

**Fable** is an one stop solution to solve all the growing needs of the administrators. It is a combination of multiple individual components stitched together in a coherent manner. These components helps administrators define and templatize the topology of their product along with it's dependencies. Once these topologies are defined, **Fable** will take care of instatiation and upkeep of these topologies, all the while capturing rich set of metrics and usage statistics. It also provides an option to templatize the topology, such that it can be reused for instantiation. Along with the pre-built components, a frame work to build customizable plugins is provided, such that users can create their own customized components to administer either the latest products or any custom built applications. Custom built plugins can be seemlessly integrated such that all the existing components interact and share data across them. Both the custom built products and configuration templates can be updated directly, using standard SDLC mechanisms, like Git. **Fable** can also hlep administrators with discerning the health mutiple instations of different products.

**Components:**
1. **Configuration Manager & templatizer**
2. **Process & Node Discoverer**
3. **License Manager**
4. **Job Manager & Automator**
5. **Entitlement/Account Manager**
6. **Analysis tools**
7. **Plugins framework for specialized tasks/duties**
8. **Documentation or Knowledge Store**


Data base administrators in a large firm are responsible for managing hundreds of different data bases and while the need for new data bases of all kinds keeps on growing. Each data base can be of different types and different capacity & usability requirements. Using **fable**, administrators can define a configuration topolgy and convert it into a template with right set of classifications, depending on the capacity & usability requirements. Once an topology configuration template is added to fable's collection, it can be used for instation of as many instances as possible. Every time an administrator want to instantiate the data base cluster, fable provides a set of available hosts that are already registered in it's host pool. The discover feature of fable helps in identifying hosts with least usage and interactions, also it recommends the hosts that are most suited for the template. Post the selection of hosts and enriching the template with necessary custom configuration specific to the technology, our product will take care of installing it on the target machines. Along with this hazel free instantiation option, any adhoc tasks like data exporters, replication, data mirgation, usage details, alerts on threshold breaches, etc., can be implements using either the custom plugins or the option provide the data base vendor.

Development work in progress.....
