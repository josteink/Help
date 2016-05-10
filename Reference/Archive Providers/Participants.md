Date: 2016-05-10

"Participants"
--------------

This provider name is implemented by the class SuperOffice.CRM.ArchiveLists.ParticipantsProvider inside NetServer's SODatabase assembly.

### Supported Entities

|                |                |
|----------------|----------------|
| associate      | Associate      |
| resource       | Resource:      |
| externalPerson | External users |

### Supported Columns

|                              |                                                                                                                                                                                                               |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ownerAssociateIdInformation  | Owner's Associate ID (associate)                                                                                                                                                                              
                                Associate ID of the user specified as owner of the follow-up *(Not OrderBy-able)*                                                                                                                              |
| inhibitConflictsInformation  | (SR\_INHIBIT\_CONFLICTS) (bool)                                                                                                                                                                               
                                ((SR\_INHIBIT\_CONFLICTS\_TOOLTIP)) *(Not OrderBy-able)*                                                                                                                                                       |
| startTimeInformation         | Start time (datetime)                                                                                                                                                                                         
                                Information for data fetcher, specifies start time for conflict checker *(Not OrderBy-able)*                                                                                                                   |
| endTimeInformation           | End time (datetime)                                                                                                                                                                                           
                                Information for data fetcher, specifies end time for conflict checker *(Not OrderBy-able)*                                                                                                                     |
| dateInformation              | Date information (date)                                                                                                                                                                                       
                                Date information, used by conflict checker *(Not OrderBy-able)*                                                                                                                                                |
| getAllRows                   | GetAll (bool)                                                                                                                                                                                                 
                                (Get all rows of archive - use with care, you may be fetching the whole database) *(Not OrderBy-able)*                                                                                                         |
| icon                         | *(No RestrictionType)*                                                                                                                                                                                        
                                Icon indicating participant type *(Not OrderBy-able)*                                                                                                                                                          |
| sendEmail                    | *(No RestrictionType)*                                                                                                                                                                                        
                                Icon indicating whether the participant should be sent e-mail *(Not OrderBy-able)*                                                                                                                             |
| seen                         | *(No RestrictionType)*                                                                                                                                                                                        
                                Icon indicating whether the participant has seen the invitation *(Not OrderBy-able)*                                                                                                                           |
| status                       | Status *(No RestrictionType)*                                                                                                                                                                                 
                                Shows any conflicts with other follow-ups *(Not OrderBy-able)*                                                                                                                                                 |
| associateEmailsInformation   | E-mail ID (int)                                                                                                                                                                                               
                                ((SR\_INFORMATION\_BOOKINGEMAILS\_TOOLTIP)) *(Not OrderBy-able)*                                                                                                                                               |
| appointmentRestrictionId     | Follow-up ID (int)                                                                                                                                                                                            
                                ID of the follow-up to fetch participants for *(Not OrderBy-able)*                                                                                                                                             |
| firstName                    | First Name ()                                                                                                                                                                                                 
                                Displays the contact's first name *(Not OrderBy-able)*                                                                                                                                                         |
| lastName                     | Last name ()                                                                                                                                                                                                  
                                Displays the contact's last name *(Not OrderBy-able)*                                                                                                                                                          |
| middleName                   | Middle Name ()                                                                                                                                                                                                
                                Displays the contact's middle name. *(Not OrderBy-able)*                                                                                                                                                       |
| fullName                     | Contact *(No RestrictionType)*                                                                                                                                                                                
                                Displays the contact an activity is linked to *(Not OrderBy-able)*                                                                                                                                             |
| contactId                    | Company ID ()                                                                                                                                                                                                 
                                Database ID of the company the user belongs to *(Not OrderBy-able)*                                                                                                                                            |
| mrMrs                        | Mr/Ms ()                                                                                                                                                                                                      
                                Displays whether the contact is addressed as Mr or Ms *(Not OrderBy-able)*                                                                                                                                     |
| title                        | Title ()                                                                                                                                                                                                      
                                Displays whether the contact is addressed as Mr or Ms *(Not OrderBy-able)*                                                                                                                                     |
| associateDbId                | ID (associate)                                                                                                                                                                                                
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| contactName                  | Owning company *(No RestrictionType)*                                                                                                                                                                         
                                Name of the company the user belongs to *(Not OrderBy-able)*                                                                                                                                                   |
| contactDepartment            | Owning department *(No RestrictionType)*                                                                                                                                                                      
                                (\[SR\_ASSOCCONTACT\_DEPT\_TOOLTIP) *(Not OrderBy-able)*                                                                                                                                                       |
| contactFullName              | Owner *(No RestrictionType)*                                                                                                                                                                                  
                                Name and department of the company the user belongs to *(Not OrderBy-able)*                                                                                                                                    |
| personEmailsInformation      | E-mail ID (int)                                                                                                                                                                                               
                                ((SR\_INFORMATION\_BOOKINGEMAILS\_TOOLTIP)) *(Not OrderBy-able)*                                                                                                                                               |
| personId                     | DB ID (int)                                                                                                                                                                                                   
                                Displays the database ID of a contact *(Not OrderBy-able)*                                                                                                                                                     |
| fullNameWithContact          | Contact and company *(No RestrictionType)*                                                                                                                                                                    
                                The fully formatted contact name, and full company name *(Not OrderBy-able)*                                                                                                                                   |
| hasInfoText                  | Info (bool)                                                                                                                                                                                                   
                                Displays an icon indicating if there is additional information available about the contact *(Not OrderBy-able)*                                                                                                |
| hasInterests                 | Interests (bool)                                                                                                                                                                                              
                                Displays an Icon indicating if the contact has active interests *(Not OrderBy-able)*                                                                                                                           |
| position                     | Position (listAny)                                                                                                                                                                                            
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personNumber                 | Number (string)                                                                                                                                                                                               
                                Displays the contact's number *(Not OrderBy-able)*                                                                                                                                                             |
| academic                     | Academic title (string)                                                                                                                                                                                       
                                Shows a person's academic title *(Not OrderBy-able)*                                                                                                                                                           |
| personCountry                | Country (listAny)                                                                                                                                                                                             
                                ((SR\_SEARCH\_COUNTRY\_TOOLTIP)) *(Not OrderBy-able)*                                                                                                                                                          |
| personNoMail                 | No Mailings (bool)                                                                                                                                                                                            
                                Displays the contact's No Mailings checkbox *(Not OrderBy-able)*                                                                                                                                               |
| rank                         | Rank (int)                                                                                                                                                                                                    
                                Displays a contact's current rank *(Not OrderBy-able)*                                                                                                                                                         |
| birthdate                    | Birthdate *(No RestrictionType)*                                                                                                                                                                              
                                Displays the contact's date of birth *(Not OrderBy-able)*                                                                                                                                                      |
| associateType                | Associate type *(No RestrictionType)*                                                                                                                                                                         
                                Displays an icon indicating if a person is an associate or external person with log-in rights and currently online \\This information is updated only once while the archive is loading. *(Not OrderBy-able)*  |
| retired                      | Former employee (bool)                                                                                                                                                                                        
                                Indicates whether the contact has retired/left the company *(Not OrderBy-able)*                                                                                                                                |
| email/emailProtocol          | Protocol (string)                                                                                                                                                                                             
                                E-mail protocol, such as SMTP *(Not OrderBy-able)*                                                                                                                                                             |
| email/emailAddress           | E-mail (string)                                                                                                                                                                                               
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| email/emailDescription       | Description (string)                                                                                                                                                                                          
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/contactId      | Company ID *(No RestrictionType)*                                                                                                                                                                             
                                Database ID of company *(Not OrderBy-able)*                                                                                                                                                                    |
| personContact/name           | Company name *(No RestrictionType)*                                                                                                                                                                           
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/department     | Department *(No RestrictionType)*                                                                                                                                                                             
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/nameDepartment | Company *(No RestrictionType)*                                                                                                                                                                                
                                Displays the company an activity is linked to *(Not OrderBy-able)*                                                                                                                                             |
| personContact/hasInfoText    | Info *(No RestrictionType)*                                                                                                                                                                                   
                                Displays an icon indicating if there is additional information available about the contact *(Not OrderBy-able)*                                                                                                |
| personContact/hasInterests   | Interests *(No RestrictionType)*                                                                                                                                                                              
                                Displays an Icon indicating if the contact has active interests *(Not OrderBy-able)*                                                                                                                           |
| personContact/associateId    | Our Contact *(No RestrictionType)*                                                                                                                                                                            
                                The user who is Our Contact on the company card *(Not OrderBy-able)*                                                                                                                                           |
| personContact/category       | Category *(No RestrictionType)*                                                                                                                                                                               
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/business       | Business *(No RestrictionType)*                                                                                                                                                                               
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/country        | Country *(No RestrictionType)*                                                                                                                                                                                
                                This criterion corresponds to the Country field on the Company card. *(Not OrderBy-able)*                                                                                                                      |
| personContact/number         | Number *(No RestrictionType)*                                                                                                                                                                                 
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/code           | Code *(No RestrictionType)*                                                                                                                                                                                   
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/orgnr          | VAT no *(No RestrictionType)*                                                                                                                                                                                 
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/stop           | Stop *(No RestrictionType)*                                                                                                                                                                                   
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/contactNoMail  | No mailings (company *(No RestrictionType)*                                                                                                                                                                   
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/registered     | Registered *(No RestrictionType)*                                                                                                                                                                             
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| personContact/lastChanged    | Last Changed *(No RestrictionType)*                                                                                                                                                                           
                                *(Not OrderBy-able)*                                                                                                                                                                                           |
| associateRestrictionId       | Associate ID (int)                                                                                                                                                                                            
                                IDs of associates to be displayed as participants *(Not OrderBy-able)*                                                                                                                                         |
| groupRestrictionId           | Group ID (int)                                                                                                                                                                                                
                                ID of group with members to be displayed as participants *(Not OrderBy-able)*                                                                                                                                  |
| resourceRestrictionId        | Resource ID (int)                                                                                                                                                                                             
                                ID of resources to be displayed as participants *(Not OrderBy-able)*                                                                                                                                           |
| externalPersonRestrictionId  | Contact ID (int)                                                                                                                                                                                              
                                ID of external persons to be displayed as participants *(Not OrderBy-able)*                                                                                                                                    |

See also: ArchiveProviderFactory.

[Restriction Types](-Restriction%20Types.htm)