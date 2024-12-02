+-----------------------------------------------------------------------+
| **Group Operational Manual**                                          |
|                                                                       |
| ![](./image1.png){width="2.6770833333333335in"                  |
| height="0.4791666666666667in"}                                        |
+=======================================================================+
+-----------------------------------------------------------------------+

> OPCO = IBERIA
>
>  
>
> Application / Service Name = SIC022-SME-ONBUSINESS - CALL CENTER 
>
> Colloquial Names/Alias Names = SME-Onbusiness-IB Call Center

**Revision History:**

  ------------------------------------------------------------------------------------
  **Name**       **Version**   **Reason for change**          **Status**    **Date**
  -------------- ------------- ------------------------------ ------------- ----------
  **Bhawna Pal** ***V1.0***    ***Draft versión***            ***In         ***11th
                                                              progress***   Nov 24***

                                                                            

                                                                            

                                                                            

                                                                            

                                                                            

                                                                            
  ------------------------------------------------------------------------------------

Table of Contents

[[***1.***      ***APPLICATION / SERVICE OVERVIEW\_
3***]{.underline}](#_Toc79141809)

> [[**1.1**         **Application / Service Description\_
> 3**]{.underline}](#_Toc79141810)
>
> [[**1.2**         **OPCO Scope\_ 3**]{.underline}](#_Toc79141811)
>
> [[**1.3**         **Architecture Diagram\_
> 3**]{.underline}](#_Toc79141812)
>
> [[**1.4**         **Application / Service Information\_
> 3**]{.underline}](#_Toc79141813)
>
> [[**1.5**         **Application Software Details
> 3**]{.underline}](#_Toc79141814)
>
> [[**1.6**         **User Interface\_ 3**]{.underline}](#_Toc79141815)
>
> [[**1.7**         **Feeds & Dependencies
> 4**]{.underline}](#_Toc79141816)
>
> [[**1.8**         **Network Information\_
> 4**]{.underline}](#_Toc79141817)
>
> [[**1.9**         **BCP -- Business Continuity Plan\_
> 4**]{.underline}](#_Toc79141818)
>
> [[**1.10**      **HA Information\_ 5**]{.underline}](#_Toc79141819)
>
> [[**1.11**      **Batch Jobs 5**]{.underline}](#_Toc79141820)

[[***2.***      ***KEY CONTACTS 5***]{.underline}](#_Toc79141821)

> [[**2.1**         **Key Users 5**]{.underline}](#_Toc79141822)
>
> [[**2.2**         **Application Support Team\_
> 5**]{.underline}](#_Toc79141823)
>
> [[**2.3**         **Escalation Matrix\_
> 5**]{.underline}](#_Toc79141824)
>
> [[**2.4**         **Other Application Support Team\_
> 5**]{.underline}](#_Toc79141825)
>
> [[**2.5**         **Infrastructure Support Team\_
> 6**]{.underline}](#_Toc79141826)
>
> [[**2.6**         **Third Party/Suppliers Details
> 6**]{.underline}](#_Toc79141827)

[[***3.***      ***SERVER & DATABASE INFORMATION\_
6***]{.underline}](#_Toc79141828)

> [**[3.1   SERVER AND DATABASE INFORMATION\_
> 6]{.underline}**](#_Toc79141829)
>
> [**[3.2   SERVER CONFIGURATION REQUIREMENTS\_
> 7]{.underline}**](#_Toc79141830)
>
> [**[3.3   INCOMPATABILITIES\_ 7]{.underline}**](#_Toc79141831)
>
> [**[3.4   PERFORMANCE REQUIREMENTS\_ 7]{.underline}**](#_Toc79141832)

[[***4.***      ***MONITORING & AUTOMATION\_
7***]{.underline}](#_Toc79141833)

[[***5.***      ***OPERATORS PROCEDURES
8***]{.underline}](#_Toc79141834)

[[***6.***      ***DATA SECURITY\_ 8***]{.underline}](#_Toc79141835)

[[***7.***      ***APPENDIX\_ 8***]{.underline}](#_Toc79141836)

[[***8.***      ***SUPPORT MODEL 8***]{.underline}](#_Toc79141837)

***\
***

**[1.APPLICATION / SERVICE OVERVIEW]{.underline}**

[]{#_Toc79141829 .anchor}1.1  Application / Service Description

-   **[Project Code:]{.underline}** 666348

-   **[Functionality]{.underline}**

> The Call Center Business Iberia, covering all those needs that the two
> applications Call Center Comarch do not cover.The main menu options of
> the application are:

-   Authorization of redemption: Creating authorizations reservation.

-   Upgrading: As of today\'s date, is not yet defined its functional
    operation.

-   State Authorizations consultation: consultation of all
    authorizations that are housed in the ABD System.

-   Manual Authorization cancellation: cancellation of authorizations.
    You can make partial cancellations, and totals. The cancellation is
    made ABD canceled Comarch system.

-   Comarch cancellation: cancellation of authorization in the Comarch
    system.

> By way of information, it has been said that unlike the previous
> program Call Center, here authorizations are unique reserve, whereas
> previously they were at the level of passenger.

-   **[Number of end users]{.underline}**

> Users of the various Call Centers, around 400 users

-   **[Number of concurrent users]{.underline}**

> Not more than 100 users

-   **[Location of Application Customers]{.underline}**

> Geographically distributed in Call Centers, locations initially in
> Spain and South America. No implantations are discarded in other areas
> of the globe.

1.2 OPCO Scope

Iberia

1.3 Architecture Diagram

-   **[Application Schema]{.underline}**

-   **[Hardware Architecture]{.underline}**

-   **[Process Diagram]{.underline}**

(Architecture diagram)

1.4  Application / Service Information

-   **[Application Criticality]{.underline}**

> High, it is the average principal operating Call Center for Business

-   **[Frequency of Use]{.underline}**

> Permanent
>
> Daily (24 hours x 365 days)

-   **[Critical time slot]{.underline}** This is a service 8 x 5 or 8 x
    > 7, due to the geographical dispersion of its members must be
    > treated as a system level 24 x 7.

  -----------------------------------------------------------------------
  **Service Level**                   SL4
  ----------------------------------- -----------------------------------
  **Application Code as in Service    SIC022
  Now**                               

  **Application ID as in Service      SIC022 - MODULO CALL CENTER DE LA
  Now**                               APLICACION ON BUSINESS / CIP
  -----------------------------------------------------------------------

1.5 Application Software Details

-   **[Application Type]{.underline}**

-   **[Source Language]{.underline}**

> Services: Java.
>
> Application: Java.
>
> Front: JavaScript (JS framework Angle).

-   **[Localization of Source Code in Repository (Github) and Code
    > Quality Metrics]{.underline}**

> [commerical-management\--sic022\--servicios-rest-cip\--accrualquote-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--gestiontarjetas-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--globalauthorization-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--member-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--redemptionfarequote-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--redemption-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--resiber-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--user-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--pcicard-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--comun-rest-cip]{.underline}
>
> [commerical-management\--sic022\--servicios-rest-cip\--wsciptokenizadoclient-rest-cip]{.underline}
>
> [commerical-management\--sic022---frontend]{.underline}
>
> [commerical-management\--sic022\--proxycip\--backend]{.underline}

-   **[SFTP]{.underline}**

> [N/A]{.underline}

-   **[Mail]{.underline}**

> [N/A]{.underline}

-   **[DBLINK]{.underline}**

> [N/A]{.underline}

-   **[SQM]{.underline}**

> [N/A]{.underline}

-   **[SCORT]{.underline}**

> [N/A]{.underline}

-   **[STD]{.underline}**

> [N/A]{.underline}

-   **[Other Connections]{.underline}**

> [N/A]{.underline}

-   **[URLS]{.underline}**

> [Production:
> [*https://awsweb.corp.iberia.es/CallCenterCip/#/*](https://awsweb.corp.iberia.es/CallCenterCip/#/)]{.underline}
>
> [Pre-Production :
> [*https://awswebpre.corp.iberia.es/CallCenterCip/#/*](https://awswebpre.corp.iberia.es/CallCenterCip/#/)]{.underline}

-   **[Colas MQ]{.underline}**

> [N/A]{.underline}

**Software Details on the server**:

Example:

  -----------------------------------------------------------------------
  **Name**                       **Version**
  ------------------------------ ----------------------------------------
  Oracle Client                  Oracle Database 11g Enterprise Edition
                                 Releas 11.2.0.3.0

  MQ Manager                     N/A

  Perl                           N/A
  -----------------------------------------------------------------------

1.6  User Interface

-   **[Configuration/Installation in Client Post]{.underline}**

-   **[URL]{.underline}**

-   [Production:
    [*https://awsweb.corp.iberia.es/CallCenterCip/#/*](https://awsweb.corp.iberia.es/CallCenterCip/#/)]{.underline}

-   [Pre-Production :
    [*https://awswebpre.corp.iberia.es/CallCenterCip/#/*](https://awswebpre.corp.iberia.es/CallCenterCip/#/)]{.underline}

-   **[LDAP User]{.underline}**

> DOES NOT APPLY

-   **[OAM]{.underline}**

> DOES NOT APPLY

-   **[AD User]{.underline}**

> DOES NOT APPLY

-   **[Other]{.underline}**

> DOES NOT APPLY

1.7  Feeds & Dependencias

-   **[Name, Path, and Permissions of Shared Resources]{.underline}**

-   **[External Services:]{.underline}**

-   *[IB.com :]{.underline}
    <https://pciservice.corp.iberia.es/intranet/PCI>*

-   *[Resiber : http: //redencionpymes.ib/RedencionWS.asmx]{.underline}*

-   *[Comarch :
    https://onbusiness.iberia.com/services/CLMService?wsdl]{.underline}*

-   *[IBIS:]{.underline}
    <https://ibisservices.iberia.com/api/sse-orm/rs/v3/order/import/locator/surname>*

-   Comarch in two variants:

> \- Single-Sign-On from the web front.
>
> \- Invoking SOAP Web services.

-   **[Users on servers and databases]{.underline}**

```{=html}
<!-- -->
```
-   **[Database Connections:]{.underline}**

> BDRACL1, BDRACL2, BDRACL3, BDRACL4
>
> Host: bdracl1 / 2/3/4
>
> Instance / Service: ibcom
>
> Port: 1521
>
> User: cipservices

-   **[Remarks]{.underline}**

1.8  Network Information

-   **[Application connectivity needs]{.underline}**

-   **[Services in Balancers]{.underline}**

-   **[Permissions in Firewall]{.underline}**

> (Update Network information such as Firewall along with FWR ID for
> different rules, Load balancers, poolname , certificates details
> (SSL/TLS ) along with expiry date).

Example:

**Firewall:**

  ----------------------------------------------------------------------------------
  **S.    **FWR   **Firewall   **Environment**   **Description**
  No.**   ID**    details**                      
  ------- ------- ------------ ----------------- -----------------------------------
  1       XXXX                 PRD               This Firewall request is to enable
                                                 communication between:\
                                                 XXX and XXX

                                                 
  ----------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------------------
  **S.    **LB   **BIGIP   **Application**   **Environment**   **Description**
  No.**   ID**   No**                                          
  ------- ------ --------- ----------------- ----------------- ---------------------------------
  1       XXXX                               PRD               Load balancing of Live traffic to
                                                               a pair of XXX/XXX Proxy Servers.

  2       XXXX                               PRD               Load balancer request to access
                                                               BIS URL using \"XXX.com\".
  ----------------------------------------------------------------------------------------------

**Load Balancer Details:**

1.9  BCP -- Business Continuity Plan ** **

-   **[Does the Unavailability of the Application Affect the
    > Availability of the entire Service? :]{.underline}**

> NO

1.10  HA Information

> N/A

1.11  Batch Jobs

-   **[Programs and Procedures involved]{.underline}**

> N/A

-   **[PROCESS Names]{.underline}**

> N/A[]{#_Toc79141821 .anchor}

**[2.KEY CONTACTS]{.underline}**

2.1  Key Users

-   **[Clients]{.underline}**

> List the key users who will be accessing this application and where
> they are located.

  -------------------------------------------------------------------------
  **Name**         **Role /             **Phone Number**  **Location**
                   Responsibility**                       
  ---------------- -------------------- ----------------- -----------------
   Flavio Jose      Product Owner Rev                      Spain
  Canoto Gumelli   Man & Sales                            

  San Jose         MANAGER                                DESARROLLO
  Fernandez,                                              COMERCIAL
  Carlos                                                  

  de Lara Nieto,   SENIOR MANAGER                         Hunting
  Miguel                                                  

  Luis Carlos      ASM                                    Spain
  Munoz Prieto                                            
  -------------------------------------------------------------------------

2.2  Application Support Team

-   **[Name, phone and support schedule]{.underline}**

> Office Hours: 9:00 to 19:00 CET from Monday to Friday.

-   Bhawna Pal - +91-8447864952 (NIIT.bpal@iberia.es)

-   Bhavika Chaudhary : +91-7206831136 (COFO.bchaudhary@iberia.es)

-   Sarthak Gupta : +91- 7985050335 (COFO.sgupta@iberia.es)

-   Rishabh Shukla : +91 -- 8953609626 (<COFO.rshukla@iberia.es>)

```{=html}
<!-- -->
```
-   **[Service Now Group]{.underline}**

  -------------------------------------------------------------------------------------------------
  **Support   **Role /           **Service Now Queue**   **Phone Number & Email ID** **Location**
  Team Name** Responsibility**                                                       
  ----------- ------------------ ----------------------- --------------------------- --------------
   Support     Support Team       APPSUP_SSRML_LOYALTY    SupportLoyalty@iberia.es    INDIA
  Loyalty                                                                            

                                                                                      

                                                                                      
  -------------------------------------------------------------------------------------------------

.3  Escalation Matrix

-   **[Author / Responsible for Development / Production
    > Manager]{.underline}**

  --------------------------------------------------------------------------
  **Escalation   **Name & Role**  **Phone Number &      **Support Hours**
  Level**                         Email ID**            
  -------------- ---------------- --------------------- --------------------
  1^st^ Level                                           

  2nd Level --                                          
  IAG SDM's/ASM                                         
  --------------------------------------------------------------------------

2.4  Other Application Support Team

-   **[Specify other media: N/A]{.underline}**

  --------------------------------------------------------------------------
  **Support    **Role /           **Service Now **Phone       **Location**
  Team Name**  Responsibility**   Queue**       Number &      
                                                Email ID**    
  ------------ ------------------ ------------- ------------- --------------
                                                               

                                                              

                                                               

                                                               
  --------------------------------------------------------------------------

2.5   Infrastructure Support Team

-   **[Specify other media]{.underline}**

> Note: All Infrastructure support queues that are related to this
> application should be listed down below.

  --------------------------------------------------------------------------
  **Support    **Role /           **Service Now **Phone       **Location**
  Team Name**  Responsibility**   Queue**       Number**      
  ------------ ------------------ ------------- ------------- --------------
                                                               

                                                               

                                                               
  --------------------------------------------------------------------------

2.6   Third Party/Suppliers Details

-   **[Specify other media]{.underline}**

  ------------------------------------------------------------------------
  **Supplier/3rd   **Role /               **Support         **Phone
  Party Name**     Responsibility**       Queue/Managed     Number/
                                          By**              Location**
  ---------------- ---------------------- ----------------- --------------
   Comarch          Service Provider       APPSUP_CIP        

  IB.com           Service Provider       APPSUP_IBIS        

   Resiber          Service Provider       APPSUP_RSV        

   IBIS             Service Provider       APPSUP_IBIS      
  ------------------------------------------------------------------------

[]{#_Toc79141828 .anchor}**[3.SERVER & DATABASE
INFORMATION]{.underline}**

3.1   SERVER AND DATABASE INFORMATION

-   **[Server]{.underline}**

-   **[Operating system :]{.underline}**

-   **[Database Volume]{.underline}**

> First year \<1GB (data + indexes). annual increase \<1GB (data +
> indexes).
>
> Database server: bdracl1 / 2/3/4

-   **[Volume and name of system files. Specify Server]{.underline}**

-   **[Database Management System]{.underline}**

> SIC022 application Database is managed by Comarch and PCI cards
> information is stored in Ibcom database.
>
> BDRACL1, BDRACL2, BDRACL3, BDRACL4
>
> Host: bdracl1 / 2/3/4
>
> Instance / Service: ibcom
>
> Port: 1521
>
> User: cipservices

-   **[Test Environment]{.underline}**

-   **[PRE-Production Environment]{.underline}**

-   **[DB Instances and Servers]{.underline}**

-   **[APPLICATION Server (Weblogic/Tomcat)]{.underline}**

**Server:**

+-------+---+----------+------------------+-----------+--------+-----+
| **S   |   | **Envir  | **               | *         | **S    | **  |
| erver |   | onment** | Function/Type ** | *Domain** | ervice | Str |
| Name  |   |          |                  |           | /Alias | ess |
| &     |   | prd/dev  | Applicat         | Ex:       | Name & | T   |
| IP**  |   | /tst/uat | ion/Database/MQ, | XXXXX.    | IP**   | est |
|       |   |          | etc              | baplc.com |        | s** |
| XXXXX |   |          |                  |           | XXXXX  |     |
| (     |   |          |                  |           | (163.  |     |
| 163.X |   |          |                  |           | X.X.X) |     |
| .X.X) |   |          |                  |           |        |     |
+=======+===+==========+==================+===========+========+=====+
|       |   |          |                  |           |        |     |
+-------+---+----------+------------------+-----------+--------+-----+
|       |   |          |                  |           |        |     |
+-------+---+----------+------------------+-----------+--------+-----+
|       |   |          |                  |           |        |     |
+-------+---+----------+------------------+-----------+--------+-----+
|       |   |          |                  |           |        |     |
+-------+---+----------+------------------+-----------+--------+-----+

**Database:** Information regarding Comarch database is not with us.
However IB.com database related information is provided in the below
table.

  -----------------------------------------------------------------------
  **Database        **Active -- Node 1**      **Standby -- Node 2**
  Nodes**                                     
  ----------------- ------------------------- ---------------------------
  Server Name & IP  bdracl1 / 2/3/4           BALxxxxPRDxxx (163.X.X.X)

  DB Instance Names                            

  DB Service Names   ibcom                     

  RAC Cluster, IP &                           
  Nodes                                       
  -----------------------------------------------------------------------

[]{#_Toc79141830 .anchor}3.2   SERVER CONFIGURATION REQUIREMENTS

-   **[Detail specific configuration]{.underline}**

-   **[Remarks]{.underline}**

-   **[Specify other needs]{.underline}**

-   **[Connection Data]{.underline}**

-   **[Internet Information Server]{.underline}**

-   **[Specify other Software products]{.underline}**

-   **[Stress and Performance Testing]{.underline}**

-   **[Recovery Tests]{.underline}**

-   **[Additional Requirements]{.underline}**

[]{#_Toc79141831 .anchor}3.3   INCOMPATABILITIES

-   **[Specify other Software products]{.underline}**

[]{#_Toc79141832 .anchor}

3.4   PERFORMANCE REQUIREMENTS

-   []{#_Toc79141833 .anchor}**[CPU consumption]{.underline}**

> Not Significant

**[4.MONITORING & AUTOMATION]{.underline}**

-   **[Application-specific alerts (Item and Location-Alert Text and
    > Support Group)]{.underline}**

> No Specific Alerts

-   **[List of Alerts Associated with LOGS]{.underline}**

Application Process/Services:

  --------------------------------------------------------------------------------
  **Server   **Process/Service   **Trigger      **Operator Recovery **Escalation
  Name**     Monitored**         condition**    Actions**           Policy along
                                                                    with SEV
                                                                    (1/2/3/4)**
  ---------- ------------------- -------------- ------------------- --------------
                                                Reference/Link to    
                                                instruction in      
                                                Section 5           

  --------------------------------------------------------------------------------

>  

Web Server (Apache/Tomcat, etc):

  -------------------------------------------------------------------------
  **Server   **Instance      **Trigger      **Operator       **Escalation
  Name**     Monitored**     condition**    Recovery         Policy along
                                            Actions**        with SEV
                                                             (1/2/3/4)**
  ---------- --------------- -------------- ---------------- --------------
                                            Reference/Link    
                                            to instruction   
                                            in Section 5     

  -------------------------------------------------------------------------

[]{#_Toc79141834 .anchor}

**[5.OPERATORS PROCEDURES]{.underline}**

-   **[Operation/Exploitation Manual]{.underline}**

> List all application/standard/nonstandard or special operator
> procedures including commands.

Location of scripts and specify if a user of root is required for
processes/scripts.

Check status/start/stop procedures/commands.

Please also include any expected responses received after command has
been entered.

List the escalation policy along with the Severity, SVD group, etc

> Note: Application support teams need to ensure that all required level
> of monitoring is configured for this application.

Example:

-   Application Level -- Application specific monitoring and callouts

-   MQ, Apache, WebLogic etc.

-   File Systems

-   Database

-   Data Loss & Management

[]{#_Toc79141835 .anchor}

**[6.DATA SECURITY]{.underline}**

-   []{#_Toc79141836 .anchor}**[Backup Frequency]{.underline}**

-   **[Data Security]{.underline}**

List how data is encrypted and details like where it is stored etc.,

**[7.APPENDIX]{.underline}**

-   **[Remarks]{.underline}**

> List any necessary details that should be communicated to OPS BRIDGE
> (L2) or taken into consideration during recovery actions and any other
> information that would be appropriate.

**[8.SUPPORT MODEL]{.underline}**

> SIR team will update the link to SharePoint site ([[Agreed Support
> Model]{.underline}](https://baplc.sharepoint.com/sites/ServiceTransition/Service%20Ops%20Documents/Agreed%20Support%20Models/Forms/AllItems.aspx?viewpath=/sites/ServiceTransition/Service%20Ops%20Documents/Agreed%20Support%20Models/Forms/AllItems.aspx))
> where the Support Model diagram is stored, which will be shared by SLM
> team once the support model is agreed with them.
