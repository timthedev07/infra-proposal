![](media/image1.png){width="1.5493055555555555in"
height="0.8208333333333333in"}

> TECHNICAL SPECIFICATIONS FOR
>
> DEVELOPMENT OF A
>
> SOFTWARE
>
> Ivan Likhosherst, Mykola Starovoit
>
> ![](media/image2.png){width="0.8297495625546807in"
> height="0.5236111111111111in"}

FEBRUARY 25, 2026

# CONTENTS  {#contents .unnumbered}

1.  **PURPOSE
    \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\....
    3**

2.  **TERMS AND DEFINITIONS
    \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...
    3**

3.  **SCOPE OF WORK
    \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.....
    4**

4.  **MODULES
    \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\....
    4**

## 4.1. IDENTITY MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\... 4 4.2. AUTHENTICATION AND AUTHORISATION MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.... 5 4.3. BUSINESS MANAGEMENT MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.... 6 4.4. BUSINESS CLIENTS MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\..... 7 4.5. PERSONNEL MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.... 9 4.6. SERVICES MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.... 10 4.7. SCHEDULE MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.... 11 4.8. booking MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\... 12 4.9. NOTIFICATIONS MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\..... 13 4.10. MARKETING MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.... 14 4.11. PAYMENTS MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\..... 15 4.12. LOYALTY AND PREPAYMENT MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\... 17 4.13. REPORT MODULE \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\.... 19  {#identity-module-.....................................................................................................................-4-4.2.-authentication-and-authorisation-module-..............................................................................................-5-4.3.-business-management-module-..........................................................................................................-6-4.4.-business-clients-module-.................................................................................................................-7-4.5.-personnel-module-.........................................................................................................................-9-4.6.-services-module-............................................................................................................................-10-4.7.-schedule-module-.........................................................................................................................-11-4.8.-booking-module-...........................................................................................................................-12-4.9.-notifications-module-.......................................................................................................................-13-4.10.-marketing-module-......................................................................................................................-14-4.11.-payments-module-..........................................................................................................................-15-4.12.-loyalty-and-prepayment-module-...................................................................................................-17-4.13.-report-module-...............................................................................................................................-19 .unnumbered}

5.  **PRICING AND SUBSCRIPTION LEVELS
    \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\....
    22**

6.  **ACCESS MATRIX
    \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\....
    23**

7.  **NON-FUNCTIONAL REQUIREMENTS
    \...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\...\....
    24**

# Purpose 

> 1.1. The server part of the software complex (hereinafter referred to
> as the System) is designed to provide business logic, storage and
> processing of data for the online user registration service.
>
> 1.2. The System is a server software service that functions as an
> independent software component and does not provide for direct
> interaction with end users.
>
> 1.3. The system provides application programming interfaces (APIs) for
> interaction with external client applications, in particular:
>
> 1.3.1. Web applications
>
> 1.3.2. Mobile applications
>
> 1.4. The system is developed with the possibility of further expansion
> of functionality and integration with other software systems without
> changing the basic architectural principles.
>
> 1.5. The implementation, design and support of client interfaces are
> not included in the scope of work under this contract.
>
> 1.6. Any functionality not explicitly described in this technical
> assignment is not included in the scope of work and may be implemented
> only under a separate agreement between the parties.

# Terms and definitions 

2.1. **User** --- a natural or legal person who has an Account in the
System.

> 2.2. **End User** --- A User who uses the System to create, view, and
> manage their own service bookings.
>
> 2.3. **Business Operator** --- A User who acts on behalf of a business
> and manages services, schedules, customers, employees, and bookings
> within the relevant business.
>
> 2.4. **Platform Administrator** --- A User with extended privileges
> who administers the System at the platform level.
>
> 2.5. **An account** is a unique set of user data (login, password,
> personal information) stored in a computer system, on a website or in
> an application.

# Scope of work 

> 3.1. The functionality of the System is implemented in the form of
> separate logical modules. The implementation of each module is limited
> to the functionality described in the relevant section of this
> technical specification.

3.2. The system includes the following modules:

> 3.2.1. Identity module
>
> 3.2.2. Authentication and authorisation module
>
> 3.2.3. Business management module
>
> 3.2.4. Business client module
>
> 3.2.5. Personnel module
>
> 3.2.6. Schedule Module
>
> 3.2.7. bookings Module
>
> 3.2.8. Notifications module
>
> 3.2.9. Marketing module
>
> 3.2.10. Payments Module
>
> 3.2.11. Reports module

# Modules 

## Identity module 

> 4.1.1. Purpose of the module
>
> 4.1.1.1. The Identity Module provides for the creation, storage and
> management of System user accounts.
>
> 4.1.1.2. An account is used to identify a subject accessing the
> System\'s application programming interfaces (APIs) and may correspond
> to the following roles:

4.1.1.2.1. End user

4.1.1.2.2. Business Operator

4.1.1.2.3. Platform Administrator

> 4.1.2. Essence of an account
>
> 4.1.2.1. The system must store the following attributes for each
> Account:

4.1.2.1. Unique identifier (id)

4.1.2.1. Unique login (phone number or email)

> 4.1.2.1.3 Account status (Pending, Active, Suspended, Deactivated,
> Deleted)

4.1.2.1.4 Date and time of creation

> 4.1.2.2 The account contains only the basic data necessary for the
> identification and authentication of the User.
>
> 4.1.2.3 Data specific to a particular User role is stored in separate
> role entities and is not part of the Account.

4.1.2.4. A separate role entity is defined for each role:

4.1.2.4.1. End user --- End user profile

4.1.2.4.2. Business operator --- Business operator profile

> 4.1.2.4.3. Platform administrator --- Platform administrator profile
>
> 4.1.2.5. The structure and attributes of role profiles are defined in
> the relevant sections of this technical specification.
>
> 4.1.3. Functional requirements

4.1.3.1. The system must ensure the creation of an Account.

> 4.1.3.2. When creating an Account, the User\'s role must be determined
> in accordance with the list specified in clause 4.1.1.2.
>
> 4.1.3.3. The system must ensure that Account data is obtained using a
> unique identifier.
>
> 4.1.3.4. The system must ensure the updating of Account attributes
> within the limits of access rights.

4.1.3.5. The system must ensure that the status of the Account can be
changed.

> 4.1.3.6 The system must ensure logical deletion and blocking of the
> Account.
>
> 4.1.3.7 The system must allow authentication only for Accounts with
> Active status.

## Authentication and authorisation module 

> 4.2.1. Purpose of the module
>
> 4.2.1.1. The authentication and authorisation module verifies the
> identity of Users and controls access to the System\'s application
> programming interfaces (APIs) in accordance with User roles.
>
> 4.2.2. Authentication
>
> 4.2.2.1. The System shall ensure User authentication using the
> authentication methods specified in clauses 4.2.2.2 and 4.2.2.3,
> linked to a single User account.
>
> 4.2.2. The system must support classic authentication based on a
> unique login and access secret.
>
> 4.2.2.2.1. An email address or phone number is used as the login.
>
> 4.2.2.2.2. The access secret (password) must be stored as a
> cryptographic hash.
>
> 4.2.2.3. The system must support authentication through third-party
> identity providers (OAuth 2.0 / OpenID Connect), in particular:

4.2.2.3.1. Authentication via Google account;

> 4.2.2.4 The system must provide access tokens for authenticating API
> requests after successful user authentication, regardless of the
> authentication method selected.
>
> 4.2.2.5 The system must ensure that access tokens are updated using
> refresh tokens.
>
> 4.2.2.6 The system must reject authentication attempts for accounts
> with the status Pending, Suspended, Deactivated, Deleted.
>
> 4.2.3. Authorisation
>
> 4.2.3.1. Authorisation of access to the System API is based on User
> roles.

4.2.3.2. The System must support the roles listed in clause 4.1.1.2.

> 4.2.3.3. The System must ensure verification of access rights to each
> API operation in accordance with the User\'s role.
>
> 4.2.3.4 The system must reject API requests if the necessary access
> rights are not available.

## Business Management Module 

> 4.3.1. Purpose of the module
>
> 4.3.1.1. The Business module enables the creation and management of
> Business entities within the System.
>
> 4.3.1.2. A business is a logical unit within which services, schedules
> and bookings are managed.
>
> 4.3.2. Business Entity

4.3.2.1. The system must store the following attributes for each
Business:

4.3.2.1. Unique identifier

4.3.2.1.2 Unique owner identifier

4.3.2.1.3 Name

4.3.2.1.4. Description

4.3.2.1.5. Business type

4.3.2.1.6. Contact details (email/website/telephone)

4.3.2.1.7 Address (if specified)

4.3.2.1.8 Status

> 4.3.3. Functional requirements

4.3.3. The system must ensure the creation of a Business

> 4.3.3.2. The system must ensure that Business data is obtained by
> identifier

4.3.3.3. The system must ensure the updating of Business attributes
specified

> in clause 4.3.2.1

4.3.3.4. The system must ensure that the status of the Business can be
changed.

4.3.3.5. The system must ensure the logical deletion of the Business.

> 4.3.4. Business rules for creating a Business
>
> 4.3.4.1. When creating an Account with the role of Business Operator,
> the System must ensure the creation of a new Business associated with
> such an Account.
>
> 4.3.4.2. The created Business is automatically linked to the Business
> Operator Account as the primary Business Operator.
>
> 4.3.5. Business Statuses

4.3.5.1. The system must support the following Business statuses:

4.3.5.1.1. Active

4.3.5.1. Deactivated

4.3.5.1.3. Deleted

4.3.5.1.4. Suspended

> 4.3.5.2. Businesses with Suspended, Deactivated or Deleted status
> should not be able to create new entries.
>
> 4.3.6. User affiliation with businesses
>
> 4.3.6.1. A business operator must be associated with at least one
> Business.
>
> 4.3.6.2. The Business Operator\'s access to data is limited
> exclusively to the Business with which they are associated.
>
> 4.3.6.3. The end user is not associated with the Business at the
> account level.

## Business client module 

> 4.4.1. Purpose of the module
>
> 4.4.1.1. The Business Customer Management Module enables the creation,
> storage, and management of customer data within a specific Business.
>
> 4.4.1.2. A Business Customer is used to identify a person for whom
> service bookings are created within the relevant Business.
>
> 4.4.2. Business Client Entity
>
> 4.4.2.1. A Business Customer is a natural person for whom a booking is
> created within a specific Business for the purpose of receiving
> services.

4.4.2.2. A Business Client may:

4.4.2.2.1. be linked to an End User Account;

4.4.2.2.2. exist without a linked Account (walk-in customer).

> 4.4.2.3. If there is a linked Account, the Customer is identified by
> the unique identifier of that Account.
>
> 4.4.3. Client attributes
>
> 4.4.3.1. The system must store the following attributes for each
> Business Customer:

4.4.3.1. Unique identifier

4.4.3.1. Business identifier

4.4.3.1.3. Customer name and designation

4.4.3.1.4 Contact number and/or email address (if available)

4.4.3.1.5 Account ID (optional)

4.4.3.1.6. Date and time of creation

4.4.3.1.7. Business Client status (Active, Deleted, Suspended)

4.4.3.1.8. List of scheduled and historical bookings

> 4.4.4. Functional requirements
>
> 4.4.4. The system must ensure the creation of a Business Client within
> the relevant Business.
>
> 4.4.4. The system must ensure the receipt of Business Client data by
> identifier within the relevant Business.
>
> 4.4.4. The system must ensure the updating of Business Client
> attributes specified in clause 4.4.3.1 within the relevant Business.
>
> 4.4.4.4 The system shall ensure the receipt of a list of Business
> Clients within the relevant Business.
>
> 4.4.4.5. The system must ensure the logical deletion and blocking of
> the Business Client within the relevant Business.
>
> 4.4.5. Rules for creating/using a client when creating a booking

4.4.5.1. When creating a booking, the System must ensure:

> 4.4.5.1. for a registered End User --- the use of an existing Business
> Client associated with the Account, or the creation of a new Business
> Client linked to such an Account;
>
> 4.4.5.1.2. for a person without an Account --- the creation of a
> walk-in Business Client without linking to an Account.
>
> 4.4.6. Importing clients
>
> 4.4.6.1. The system must support the import of Business Customers from
> external data sources, including:

4.4.6.1.1. CSV files

4.4.6.1.2 XLS or XLSX files;

> 4.4.6.1.3. importing contacts from the device\'s phone book via the
> client application.
>
> 4.4.6.2. Import is carried out exclusively within the scope of a
> specific Business and is available only to the Business Operator.
>
> 4.4.6.3 During import, the System must ensure the creation of new
> Business Customers based on the transferred data.

4.4.6.4 Minimum supported fields for import:

4.4.6.4.1. Client name and designation

4.4.6.4.2. Contact telephone number and/or email address

> 4.4.6.5. If there are no mandatory import fields, the System shall
> reject the corresponding booking.

## Personnel module 

> 4.5.1. Purpose of the module
>
> 4.5.1.1. The personnel module provides management of Business
> employees who are involved in providing services and/or performing
> bookings.
>
> 4.5.1.2 Within this module, an employee is considered as an entity
> linked to a specific Business.
>
> 4.5.2. Entity Employee

4.5.2.1. The system must store the following attributes for each
Employee:

4.5.2.1.1. All fields specified in clause 4.1.2.1

4.5.2.1.2. First name and surname

4.5.2.1.3 Photo

4.5.2.1.4 Description

4.5.2.1.5 Work schedule

4.5.2.1.6. Contact details

4.5.2.1.7. Specialisation (Position)

4.5.2.1.8 Rating

> 4.5.3. Functional requirements
>
> 4.5.3. The system must ensure the creation of an Employee within the
> Business
>
> 4.5.3. The system must ensure the receipt of information about the
> Employee by identifier within the relevant Business.
>
> 4.5.3. The system must ensure the logical deletion of an Employee
> within the Business.
>
> 4.5.4. Employee statuses

4.5.4.1. The system must support the following Employee statuses:

4.5.4.1.1. Active

4.5.4.1. Suspended

4.5.4.1.3. Deleted

> 4.5.4.2. An employee with Suspended or Deleted status should not be
> used to create new bookings.
>
> 4.5.5. Connection with other modules
>
> 4.5.5. An employee can be used in the schedule module to determine
> availability.
>
> 4.5.5.2 An employee can be used in the bookings module to link a booking
> to a specific performer.
>
> 4.5.5. The detailed logic of using Employees in the schedule and
> bookings is defined in the relevant sections of this technical
> specification.

## Services Module 

> 4.6.1. Purpose of the module
>
> 4.6.1.1. The Services Module provides management of the list of
> services provided by the Business within the System.
>
> 4.6.1.2. The service defines the type of work available for bookinging
> by End Users.
>
> 4.6.1.3 The System shall provide the ability to link a Service to one
> or more Employees within the relevant Business.
>
> 4.6.2. Essence of the Service

4.6.2.1. The System shall store the following attributes for each
Service:

4.6.2.1. Unique identifier

4.6.2.1. Name

4.6.2.1.3 Description

> 4.6.2.1.4. Category, type 4.6.2.1.5. Duration

4.6.2.1.6. Buffer time

4.6.2.1.7. Cost and financial attributes

4.6.2.1.8. Status (Active, Inactive)

4.6.2.1.9 Available employees

> 4.6.3. Functional requirements

4.6.3.1. The system must ensure the creation of the Service within the
Business.

> 4.6.3. The system must ensure that information about the Service is
> obtained by identifier within the relevant Business.
>
> 4.6.3. The system must ensure the updating of the Service attributes
> specified in clause 4.6.2.1 within the Business.
>
> 4.6.3.4 A Service with Inactive status must not be used to create new
> bookings.
>
> 4.6.4. Relationship between Services and Employees

4.6.4.1. The System shall provide the ability to link one

> Service to one or more Employees within a single Business.
>
> 4.6.4.2. The system must provide the ability to link one Employee to
> several Services within one Business.
>
> 4.6.4.3. The logic of Service availability depending on the Employee
> and their schedule is determined in the schedule module.

## Schedule module 

> 4.7.1. Purpose of the module
>
> 4.7.1.1. The schedule module allows you to determine the time
> availability of the Business and Employees for creating bookings.
>
> 4.7.1.2. The schedule is used to form available time slots in the
> bookinging module.
>
> 4.7.2. Business Schedule
>
> 4.7.2.1. The system must ensure the storage of the basic working
> schedule of the Business.
>
> 4.7.2.2. The basic Business schedule defines the standard working
> hours that apply by default.
>
> 4.7.2.3 The system shall ensure that the basic Business schedule is
> updated within the relevant Business.
>
> 4.7.3. Employee Schedule
>
> 4.7.3.1. The system shall ensure the storage of the Employee\'s
> individual work schedule.
>
> 4.7.3.2. The Employee\'s individual schedule takes precedence over the
> basic Business schedule.
>
> 4.7.3.3. The Employee\'s schedule is determined solely within the
> Business to which he or she belongs.
>
> 4.7.4. Exceptions to the schedule
>
> 4.7.4.1. The system must provide the ability to define exceptions to
> the schedule (non-working days or time intervals).
>
> 4.7.4.2. Exceptions can apply to both the Business and individual
> Employees.

4.7.4.3 Exceptions take precedence over the basic and individual
schedules.

> 4.7.5. Functional requirements
>
> 4.7.5.1. The system must ensure the creation, updating and retrieval
> of Business schedule data.
>
> 4.7.5.2. The system shall ensure the creation, updating and retrieval
> of Employee schedule data.
>
> 4.7.5.3. The system shall ensure the determination of time intervals
> available for bookinging, taking into account:

4.7.5.3.1. Business schedule

4.7.5.3. Employee Schedule

4.7.5.3. Exceptions to the Schedule

## bookings module 

> 4.8.1. Purpose of the module
>
> 4.8.1.1. The bookings Module enables the creation, modification, and
> cancellation of End User bookings for Business Services, taking into
> account the schedule and availability of Employees.
>
> 4.8.1.2. A booking is the reservation of time slots for the provision
> of a specific Service by a specific Employee.
>
> 4.8.2. Essence booking

4.8.2.1. The system must store the following attributes for each booking:

4.8.2.1. Unique identifier

4.8.2.1.2 Links to other entities (service, employee, customer)

4.8.2.1.3 Start date and time

4.8.2.1.4 Status (Planned, confirmed, completed, cancelled, no_show)

4.8.2.1.5 Source of creation

4.8.2.1.6. Notes

> 4.8.3. Functional requirements

4.8.3. The system shall ensure the creation of a booking provided that:

4.8.3.1.1. Active business status

4.8.3.1.2. Active service status

4.8.3.1.3. Active employee status

> 4.8.3.1.4. Availability of an accessible time slot in accordance with
> the schedule module

4.8.3.1.5. No conflict with existing Employee bookings

> 4.8.3.2. The system must ensure that information about the booking is
> obtained by identifier within the relevant Business.

4.8.3.3. The system must ensure that a list of bookings is obtained:

> 4.8.3.3.1. for the End User --- their own bookings; 4.8.3.3.2. for the
> Business Operator --- bookings of the relevant Business.

4.8.3.4. The system must ensure the cancellation of a booking.

> 4.8.3.5. The system must ensure that the time of the booking can be
> changed, subject to the requirements of clause 4.8.3.1.
>
> 4.8.3.6. Entries with the status Completed, Cancelled, No_show cannot
> be changed.
>
> 4.8.4. Rules and restrictions
>
> 4.8.4.1. The system must not allow the creation of bookings with
> overlapping times for the same employee.

4.8.4. An end user may have several active bookings at the same time.

> 4.8.4.3. The end time of a booking is determined as the sum of the
> start time of the booking and the duration of the corresponding
> Service.

## Notification module 

> 4.9.1. Purpose of the module
>
> 4.9.1.1. The notification module generates and sends information
> messages to System Users in response to specific events.
>
> 4.9.1.2. The module is used to inform about changes in the status of
> bookings and other events specified in this technical assignment.
>
> 4.9.2. Events for notifications
>
> 4.9.2.1. The System shall generate notifications in the event of the
> following events:

4.9.2.1.1. creation of a booking;

4.9.2.1.2. a change in the time of a booking;

> 4.9.3. Notification recipients

4.9.3.1. The system shall ensure that notifications are sent to:

4.9.3.1.1. End user --- regarding their own bookings

4.9.3.1.2. The Business Operator --- regarding the bookings of the
relevant Business.

> 4.9.4. Notification channels
>
> 4.9.4.1. The system must ensure that notifications are sent through
> the following channels

4.9.4.1. Email

4.9.4.1. PUSH notifications

4.9.4.1. SMS

> 4.9.5. Content of notifications

4.9.5.1. Notifications must contain the minimum necessary information:

4.9.5.1.1. Type of event

4.9.5.1. Date and time of bookinging

4.9.5.1.3. Service name

4.9.5.1.4 Business name

> 4.9.5.2. For Business-initiated mailings, messages must contain text
> generated by the Business Operator, without the mandatory inclusion of
> the attributes specified in clause 4.9.5.1.

## Marketing module 

> 4.10.1. Purpose of the module
>
> 4.10.1.1. The marketing module provides marketing activities within
> the relevant Business, in particular discounts, promotions and promo
> codes.
>
> 4.10.1.2. Marketing mechanisms are applied to Services when creating
> bookings.
>
> 4.10.1.3. The marketing module can initiate the sending of marketing
> messages through the notification module
>
> 4.10.2. Essence of a marketing promotion
>
> 4.10.2.1. The system must store the following attributes for each
> marketing campaign:

4.10.2.1.1. Unique identifier

4.10.2.1.2. Promotion type (standard, flash_sale, happy_hours)

4.10.2.1.3. Discount type (fixed, percentage)

4.10.2.1.4 Discount amount

4.10.2.1.5 Validity period

4.10.2.1.6 Status

4.10.2.1.7. Date of creation

> 4.10.2.2. Features of share types

4.10.2.2.1. Standard

4.10.2.2.1.1. The share is valid for a specified period of time.

4.10.2.2.2. Flash sale

> 4.10.2.2.2.1. The promotion applies if the time of creation of the
> booking is within a specified interval before the start of the session
> (for example, no more than 60 minutes before the start).

4.10.2.2.3. Happy/sad hours

> 4.10.2.2.3.1. The promotion applies only to bookings whose start time
> falls within a specified time interval during the day.
>
> 4.10.3. Connection with services
>
> 4.10.3.1. The system must provide the ability to link a marketing
> promotion to one or more Services within the relevant Business.
>
> 4.10.3.2. When creating a booking, the system must take into account
> active marketing campaigns that meet the conditions of use.
>
> 4.10.4. Marketing messages
>
> 4.10.4.1. The system must provide the ability to generate and initiate
> marketing messages by the operator of the relevant Business.
>
> 4.10.4.2. Marketing messages are sent to Users via the notification
> module.
>
> 4.10.4.3. The Business operator must be able to specify the group of
> Users to whom the marketing message will be sent.
>
> 4.10.4.4. The system must provide the ability to schedule the time of
> sending a marketing message (immediate sending or delayed to a
> specified date and time).
>
> 4.10.4.5. The Business Operator must be able to select the channel for
> sending marketing messages from the list of channels specified in
> clause 4.9.4.1.
>
> 4.10.4.6. Until the actual sending of the marketing message, the
> Business Operator must be able to:

4.10.4.6.1. Edit the content of the message

4.10.4.6.2. Change the sending parameters

4.10.4.6. Delete message

4.10.4.6.4. View the generated message and its settings

> 4.10.4.7. Once sent, marketing messages cannot be changed or deleted.
>
> 4.10.5. Restrictions and rules of application
>
> 4.10.5.1. The system shall apply a discount only if the promotion has
> the status Active and is within the specified period of validity.
>
> 4.10.5.2. The final price of the service must be bookinged in the
> booking at the time of its creation.

## Payment module 

> 4.11.1. Purpose of the module
>
> 4.11.1.1. The payment module provides online and offline payment
> processing for services and prepaid products within the System.
>
> 4.11.1.2. The payment module provides integration with external
> payment services, bookinging of offline payments, and storage of
> payment transaction information.
>
> 4.11.2. Supported payment methods
>
> 4.11.2.1. The system must support the following payment methods:

4.11.2.1.1. Apple Pay;

> 4.11.2.1.2. one external payment system for accepting bank cards
> (hereinafter referred to as the Payment Provider), specified by the
> Customer prior to implementation;

4.11.2.1.3. cash payments bookinged in the System;

4.11.2.1.4. Tap-to-Pay through an integrated Payment Provider.

> 4.11.3. Types of payments
>
> 4.11.3.1. Online payment --- a payment processed through an integrated
> Payment Provider.
>
> 4.11.3.2. Offline payment --- a payment made outside the System and
> bookinged manually by the Business Operator.
>
> 4.11.3.3. Tap-to-Pay --- a payment initiated through the System and
> processed by the Payment Provider using a supported device.
>
> 4.11.4. Online payment process
>
> 4.11.4.1. After initiating an online payment, the System must create a
> payment transaction and transfer the necessary data to the relevant
> Payment Provider.
>
> 4.11.4.2. Confirmation of the success or failure of the payment is
> based on the response from the Payment Provider.
>
> 4.11.4.3. The system must ensure the processing of asynchronous
> messages (webhooks) from the Payment Provider.
>
> 4.11.5. bookinging offline payments
>
> 4.11.5.1. In the case of an offline payment, the System must allow the
> Business Operator to manually create a Payment and set its status as
> Paid.
>
> 4.11.5.2. The System does not verify the actual receipt of funds in
> the case of an offline payment.
>
> 4.11.6. Combined payment
>
> 4.11.6.1. The System shall support the possibility of combined payment
> within a single transaction.
>
> 4.11.6.2. Combined payment means the distribution of the total amount
> between two acceptable payment methods.
>
> 4.11.6.3. The system must ensure that each component of a combined
> payment is bookinged as a separate payment transaction.
>
> 4.11.6.4. The transaction shall be considered successful only if all
> components of the payment are confirmed.
>
> 4.11.6.5. If any component of the payment is unsuccessful, the System
> shall not complete the transaction.
>
> 4.11.7. Essence of \"Payment\"
>
> 4.11.7.1. The System shall store the following attributes for each
> Payment:

4.11.7.1.1. a unique identifier;

4.11.7.1.2. User identifier;

4.11.7.1.3. Business identifier;

4.11.7.1.4. payment amount;

4.11.7.1.5. payment method;

4.11.7.1.6. payment type (online/offline/Tap-to-Pay);

4.11.7.1.7. payment status (Pending, Paid, Failed, Cancelled)

4.11.7.1.8. date and time of creation.

> 4.11.8. Security
>
> 4.11.8.1. The system does not store full bank card details.
>
> 4.11.8.2. Payment data is processed exclusively on the side of the
> Payment Provider.
>
> 4.11.8.3. The system only stores technical transaction identifiers
> received from the Payment Provider.

## Loyalty and Prepayment Module 

> 4.12.1. Purpose of the module
>
> 4.12.1.1. The loyalty and subscription module supports prepayment
> mechanisms and encourages repeat customer visits, in particular
> through gift cards, subscriptions and service packages.
>
> 4.12.1.2. The module\'s mechanisms are applied when creating bookings
> and making payments.
>
> 4.12.2. Gift cards
>
> 4.12.2.1. Essence Gift card
>
> 4.12.2.1.1. The system must store the following attributes for each
> gift card:

4.12.2.1.1. card identifier;

4.12.2.1.1.2. business identifier;

4.12.2.1.1.3. unique card code;

4.12.2.1.1.4. denomination (monetary amount);

4.12.2.1.1.5. balance of funds

4.12.2.1.1.6. date of creation

4.12.2.1.1.7. expiry date (if applicable)

4.12.2.1.1.8. status (active, redeemed, expired, cancelled)

> 4.12.2.2. Functional requirements
>
> 4.12.2.2.1. The system must ensure the creation of gift cards with a
> specified denomination.
>
> 4.12.2.2. The system must ensure the possibility of partial use of the
> gift card denomination.
>
> 4.12.2.2. The amount used on a gift card must be bookinged in the
> relevant booking.
>
> 4.12.2.2.4. After the full value has been used, the card status
> changes to redeemed.
>
> 4.12.3. Memberships
>
> 4.12.3.1. Essence of a membership
>
> 4.12.3.1.1. The system shall store the following attributes for each
> subscription:

4.12.3.1.1.1. subscription identifier;

4.12.3.1.1.2. business identifier;

4.12.3.1.1.3. name;

4.12.3.1.1.4. period of validity;

4.12.3.1.1.5. cost;

4.12.3.1.1.6. list of permissible services for use

4.12.3.1.1.7. status (active, suspended, expired, cancelled)

> 4.12.3.2. Functional requirements
>
> 4.12.3.2.1. The system must ensure that the subscription is linked to
> a specific User.
>
> 4.12.3.2.2. The system must automatically apply the benefits of the
> subscription when creating a booking.

4.12.4. Service packages

> 4.12.4.1. Essence of Service Packages
>
> 4.12.4.1.1. The system shall store the following attributes for each
> service package:

4.12.4.1.1. Package identifier

4.12.4.1.1.2. Business identifier

4.12.4.1.1.3 Name

4.12.4.1.1.4 List of services included in the package

4.12.4.1.1.5 Number of available uses for each service

4.12.4.1.1.6 Cost

4.12.4.1.1.7 Period of validity

4.12.4.1.1.8. Status (active, suspended, expired, deleted)

> 4.12.4.2. Functional requirements
>
> 4.12.4.2.1. The system must ensure that the service package is linked
> to the User after payment has been made.
>
> 4.12.4.2.2. When creating a booking, the system must check for an
> active package and available uses.
>
> 4.12.4.2.3. After using the service within the package, the number of
> available uses should decrease.
>
> 4.12.5. Interaction with other modules
>
> 4.12.5.1. The module uses the Payments module to booking the fact of
> payment for gift cards, subscriptions, and packages.
>
> 4.12.5.2. The module interacts with the bookings module to
> automatically apply benefits or deduct available uses.
>
> 4.12.5.3. The final conditions for applying discounts or debits are
> bookinged in the booking.
>
> 4.12.6. Purchase and activation of loyalty products
>
> 4.12.6.1. The system must provide the possibility of purchasing
>
> gift cards, subscriptions, and service packages within the relevant
> Business.
>
> 4.12.6.2. After successful payment confirmation, the system must
> automatically create the corresponding entity (gift card, subscription
> or service package) and assign it a unique identifier or code.
>
> 4.12.6.3. The system must ensure that information about the purchased
> product, including a unique code (if available), is sent to the buyer
> or specified recipient through the communication channels provided by
> the notification module.
>
> 4.12.6.4. The Operator or User must be able to select the delivery
> channel (e-mail, SMS or other channel specified in clause 4.9.4.1).
>
> 4.12.6.5. The purchased product must be displayed in the profile of
> the corresponding User in the system.
>
> 4.12.6.6. The product is considered active only after confirmation of
> successful payment.

## Reports module 

> 4.13.1. Purpose of the module
>
> 4.13.1.1. The Reports Module provides the formation and display of
> analytical information on the activities of the relevant Business
> based on the System data.
>
> 4.13.1.2. The reporting module is designed to support management
> decision-making and performance monitoring (finance, customers,
> services, employees, bookings).
>
> 4.13.2. General functional requirements
>
> 4.13.2.1. The system must ensure the generation of reports within the
> relevant business.
>
> 4.13.2.2. The system should support filtering reports by period
> (day/week/month/arbitrary date range).
>
> 4.13.2.3. The system must support grouping of indicators by at least
> month and day.
>
> 4.13.2.4. The system must support filtering by:

4.13.2.4.1. Employee

4.13.2.4.2. Service

4.13.2.4.3. booking Status

4.13.2.4.4. Payment Status

4.13.2.4.5. booking creation channel

4.13.2.4.6. Payment method

> 4.13.2.4.6.1. The system must provide a display of aggregated
> indicators (amounts, quantities, average values) and details down to
> the level of specific bookings.
>
> 4.13.2.4.6.2. The system must provide the ability to export reports
> (e.g., CSV/PDF).
>
> 4.13.3. List of reports
>
> 4.13.3.1. Financial reports
>
> 4.13.3.1. The system should generate a \"Revenue for the period\"
> report showing:

4.13.3.1.1. Total amount of revenue

4.13.3.1.1. Number of payments

4.13.3.1.1.3. Average cheque (if data is available)

> 4.13.3.1.2. The system should generate a report \"Payments by method\"
> showing the amount and number of payments by payment method.
>
> 4.13.3.2. Customer reports
>
> 4.13.3.2.1. The system should generate a \"Number of customers\"
> report showing:

4.13.3.2.1.1. the number of unique customers for the period;

> 4.13.3.2.1.2. the number of new customers for the period (first entry
> in the system);

4.13.3.2.1.3. number of repeat customers during the period.

> 4.13.3.2.2. The system should generate a \"Customer Activity\" report
> showing the number of bookings per customer and/or frequency of visits
> (if data is available).
>
> 4.13.3.3. Reports on bookings
>
> 4.13.3.3.1. The system should generate a \"bookings for the period\"
> report showing:

4.13.3.3.1. The total number of bookings

4.13.3.3.1.2. The number of bookings by status

> (planned/confirmed/completed/cancelled/no_show or equivalent).
>
> 4.13.3.3.1.3. The system must generate a \"Cancellations and
> No-Shows\" report showing the number and percentage of
> cancelled/no_show for the period.
>
> 4.13.3.4. Reports on services
>
> 4.13.3.4.1. The system should generate a \"Service Popularity\" report
> showing the number of entries for each Service for the period.
>
> 4.13.3.4.2. The system should generate a \"Service Revenue\" report
> showing the amount of payments for each Service for the period.
>
> 4.13.3.4.3. The system must generate a \"Customers by Services\"
> report showing the number of unique customers for each Service for the
> period.
>
> 4.13.3.5. Reports on employees
>
> 4.13.3.5.1. The system should generate a report \"Income by
> Employees\" showing the amount of payments linked to the bookings of
> specific Employees for the period.
>
> 4.13.3.5.2. The system should generate a report \"Number of bookings by
> employees\" showing the number of bookings broken down by Employees and
> booking statuses.
>
> 4.13.3.5.3. The system must generate a report \"Employee remuneration
> accruals\" for a specified period.
>
> 4.13.3.5.4. The report should enable the calculation of employee
> remuneration based on:

4.13.3.5.4.1. The number of services performed

4.13.3.5.4.2. Amounts of confirmed payments for services rendered

> 4.13.3.5.4.3. Established commission discount or fixed remuneration
> rate
>
> 4.13.3.5.5. The system must provide the ability to set an individual
> commission percentage for each Employee.
>
> 4.13.3.5.6. Remuneration shall be calculated automatically on the
> basis of actual confirmed payments for the relevant period.
> 4.13.3.5.7. The report shall reflect:
>
> 4.13.3.5.7.1. the total amount of income generated by the Employee for
> the period;

4.13.3.5.7.2. the commission percentage or rate applied;

4.13.3.5.7.3. the calculated amount of remuneration;

# Pricing and subscription levels  {#pricing-and-subscription-levels .unnumbered}

5.1. Purpose

> 5.1.1. The System shall support a subscription model whereby access to
> the System\'s functionality is determined by the selected Business
> subscription level.

5.2. Subscription levels

> 5.2.1. The System shall support several subscription levels (tariff
> plans)
>
> 5.2.2. Each subscription level determines the list of available System
> functionalities

5.3. Access restrictions

> 5.3.1. The System shall restrict access to modules and functionality
> in accordance with the active Business subscription level.
>
> 5.3.2. In the event of a change or termination of subscription, the
> system must automatically update access to functionality.
>
> 5.3.3. Features that are not available for the current subscription
> level should not be available for use.

5.4. Subscription management

> 5.4.1. The system must provide the ability to purchase, renew, and
> change the subscription level.
>
> 5.4.2. The system must store information about:

5.4.2.1. the selected tariff plan;

5.4.2.2. the subscription start date;

5.4.2.3. the subscription end date;

5.4.2.4 subscription status (active, suspended, expired)

# Access Matrix  {#access-matrix .unnumbered}

6.1. General provisions

> 6.1.1. Access to the System\'s functionality is provided in accordance
> with the User\'s role
>
> and within the limits of the powers defined by this access matrix.
>
> 6.1.2. Any operation not explicitly permitted by the relevant role is
> considered prohibited.

6.2. Access Matrix for Basic Operations

+-----------------+----------------+----------------+-----------------+
| Operation/Role  | End user       | > Business     | Platform        |
|                 |                | > operator     | administrator   |
+=================+================+================+=================+
| CRUD of own     | \+             | > \+           | \+              |
| profile         |                |                |                 |
+-----------------+----------------+----------------+-----------------+
| CRUD Business   | \-             | > \+ (only     | \+              |
|                 |                | > your own)    |                 |
+-----------------+----------------+----------------+-----------------+
| CRUD            | \-             | > \+ (within   | \-              |
|                 |                | > your         |                 |
| Employees       |                | > business)    |                 |
+-----------------+----------------+----------------+-----------------+
| CRUD services   | \-             | > \+ (within   | \-              |
|                 |                | > the scope of |                 |
|                 |                | > your         |                 |
|                 |                | > business)    |                 |
+-----------------+----------------+----------------+-----------------+
| CRUD schedule   | \-             | > \+ (within   | \-              |
|                 |                | > the scope of |                 |
|                 |                | > your         |                 |
|                 |                | > business)    |                 |
+-----------------+----------------+----------------+-----------------+
| Viewing your    | \+             | > \+           | \+              |
| own bookings     |                |                |                 |
+-----------------+----------------+----------------+-----------------+
| Creating a      | \+             | > \+ (on       | \-              |
| booking          |                | > behalf of a  |                 |
|                 |                | > business)    |                 |
+-----------------+----------------+----------------+-----------------+
| Sending         | \-             | > \+ (on       | \+              |
| mailings        |                | > behalf of    |                 |
|                 |                | > your         |                 |
|                 |                | >              |                 |
|                 |                | > business)    |                 |
+-----------------+----------------+----------------+-----------------+
| Viewing         | \-             | > \-           | \+              |
| platform users  |                |                |                 |
+-----------------+----------------+----------------+-----------------+
| Blocking users  | \-             | > \-           | \+              |
| and businesses  |                |                |                 |
+-----------------+----------------+----------------+-----------------+

> 6.2.1. End users do not have access to the data of other users or
> businesses
>
> 6.2.2. Business operators do not have access to data belonging to
> other Businesses that are not associated with their account
>
> 6.2.3. The platform administrator has access to all Businesses and
> Users within the system.

# Non-functional requirements  {#non-functional-requirements .unnumbered}

7.1. General provisions

> 7.1.1. Non-functional requirements define the qualitative, technical
> and operational characteristics of the System, which it must comply
> with within the scope of this technical assignment.
>
> 7.1.2. The requirements of this section apply to the server part of
> the System and do not apply to client applications.

7.2. Reliability and availability

> 7.2.1. The System shall be designed with fault tolerance of key
> components in mind.
>
> 7.2.2. Temporary unavailability of certain auxiliary components
>
> (in particular, the notification module) shall not result in the
> complete unavailability of the main functionality of the System.
>
> 7.2.3. The Contractor does not guarantee the continuous availability
> of the System in the event of failures of external services or
> infrastructure that are not controlled by the Contractor.

7.3. Security

> 7.3.1. All software interfaces of the System must be accessible
> exclusively through a secure connection (HTTPS).
>
> 7.3.2. The System must ensure that user account data is stored in a
> secure form using modern cryptographic algorithms.
>
> 7.3.3. The system must ensure verification of API access rights in
> accordance with the roles defined in clause 4.1.2.4 of these technical
> specifications.

7.4. Logging and diagnostics

> 7.4.1. The system must ensure basic logging of technical errors on the
> server side.

7.5. Scalability

> 7.5.1. The architecture of the System must provide for the possibility
> of horizontal scaling of the server part.

7.6. Compatibility and environments

> 7.6.1. The system must provide software interfaces in JSON format over
> HTTPS.
