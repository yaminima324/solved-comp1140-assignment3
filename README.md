Download Link: https://assignmentchef.com/product/solved-comp1140-assignment3
<br>
<strong>Catalogue</strong>

The School of SEEC maintains information about its physical and online resources. SEEC have physical resources which students can borrow/loan such as cameras, speakers, phones and CDs. SEEC also have online resources which can be used such as various software that students can have access to if required.

<strong>Collections</strong>

The School have many collections of items in each respective location. A collection contains a unique name – “ES105 – Speaker”, etc. and provides the location where the collection exists physically in the building. Each physical item belongs to a collection within the School of SEEC. Likewise, the School of SEEC also provides information as to where to access and download software for student use. Each software item is a part of a collection which exists virtually and is arranged into different categories depending on the course (e.g. Engineering, Computing, etc.) that the software is related to.

<strong>Resources</strong>

The School of SEEC have many resources that they can loan students during the duration of their degree to assist them in their study or to use during their assignments. Every resource has:

<ul>

 <li>a resource ID (which is unique)</li>

 <li>a description of the item</li>

 <li>a status (e.g. ‘in use’, ‘maintenance’, ‘available’, ‘borrowed’, ‘lost’, ‘damaged’, etc.)</li>

</ul>

There are two types of resources students can use; moveable and non-moveable. Moveable resources include items such as cameras, microphones, speakers, etc. Moveable resources have a:




<ul>

 <li>name</li>

 <li>make</li>

 <li>manufacturer</li>

 <li>model</li>

 <li>year</li>

 <li>asset value</li>

</ul>

<strong> </strong>

For example, the SEEC resource database about would maintain information about cameras. Information on cameras maintained by the School include:




<ul>

 <li>Brand of camera (Canon, Nikon, Sony)</li>

 <li>Type of camera (camcorder, DSLR, action)</li>

 <li>Camera lenses (standard/general purpose, wide angle)</li>

 <li>Charge time and battery life</li>

 <li>Colour</li>

 <li>Model Number</li>

 <li>Serial Number</li>

 <li>Storage location of the cameras depending on what is loaned/used more.</li>

</ul>




Non-movable resources are resources such as classrooms, laboratories, etc. Each immovable resource has:




<ul>

 <li>maximum person capacity</li>

 <li>see location entity below for further explanation</li>

</ul>










Each resource is placed into a category, such as ALL cameras, ALL speakers, etc. Each category has a:




<ul>

 <li>unique code</li>

 <li>name</li>

 <li>description</li>

 <li>max time allowed to borrow/book (in days and/or hours)</li>

</ul>




<strong>Location</strong>

All resources have a location where they are situated that can accessed by staff members and student members alike. These locations have a:




<ul>

 <li>unique ID</li>

 <li>room</li>

 <li>building</li>

 <li>camp</li>

</ul>




<strong>Loan</strong>

Lending and reservation rights are offered to students by staff who are enrolled in courses offered by SEEC. These students and staff are known as “members” in the system. Members have a:




<ul>

 <li>unique ID (student or staff number)</li>

 <li>name</li>

 <li>address</li>

 <li>phone number</li>

 <li>email</li>

 <li>status (‘active’, ‘disabled’)</li>

 <li>comments field</li>

</ul>




Student members enrol in courses offered by SEEC. Course information abouts and student enrolments are maintained. A course offering has a:




<ul>

 <li>offering ID (which is unique)</li>

 <li>course ID (which is unique)</li>

 <li>name</li>

 <li>semester offered</li>

 <li>year offered</li>

 <li>course beginning/end date</li>

</ul>

<strong> </strong>

The loaning of an item is an entity in itself. This differs from reservation as the act of loaning a resource has different requirements and attributes. Each loan has a:




<ul>

 <li>member ID</li>

 <li>date loaned</li>

 <li>time loaned</li>

 <li>resource ID</li>

 <li>date due</li>

 <li>time due</li>

</ul>

<strong> </strong>

<strong>Privilege</strong>

Staff members can borrow/reserve resources. Staff have no limits on the number of resources that staff can use. Students are granted privileges on what they can borrow/reserve depending on the course they are enrolled in. Courses are assigned privileges to different categories of resources. Each privilege has a:




<ul>

 <li>name</li>

 <li>description</li>

 <li>a privilege category</li>

 <li>maximum number of resources that a student member can borrow/book at any given time</li>

</ul>




A member can loan moveable resources (such as cameras, speakers, etc.) if their privileges allow it. Information about the resource when it is loaned is maintained for the duration of it loan.

<strong> </strong>

<strong>New Acquisitions</strong>

New acquisitions can be made to the School by a student or staff member. An acquisition contains:




<ul>

 <li>a person requesting acquisition</li>

 <li>an item name</li>

 <li>make</li>

 <li>manufacturer</li>

 <li>model</li>

 <li>year</li>

 <li>a description of the required item</li>

 <li>its urgency</li>

</ul>




The administrator of the system assigns values to the acquitted item such as:




<ul>

 <li>admin ID</li>

 <li>status (‘acquired’, ‘pending’, etc.)</li>

 <li>a fund code</li>

 <li>vendor code</li>

 <li>price</li>

 <li>notes</li>

</ul>

<strong> </strong>

<strong>Reservations</strong>

Resources can be reserved by members as long as their privileges allow them to borrow/book that resource. The resource will be booked for pickup/use by the student or staff member at the requested date and time after a reservation is made. Reservations have the date and time the item is required and a due date and time. No two reservations should ever conflict as that becomes problematic for one of the members attempting to borrow/book the resource.

Transaction Requirements:

<strong>Data Manipulation Operations</strong>

<ul>

 <li>Insert/update/delete an item in the database</li>

 <li>Insert/update/delete a copy of item in the database</li>

 <li>Insert/update/delete the status of an item</li>

 <li>Insert/update/delete an online information source</li>

 <li>Insert/update/delete staff of the School of SEEC</li>

 <li>Insert/update/delete location of a resource</li>

 <li>Insert/update/delete members</li>

 <li>Insert/update/delete member information</li>

 <li>Insert/update/delete acquisition items</li>

 <li>Insert/update/delete reservations</li>

</ul>

<strong>Queries</strong>

<ul>

 <li>Search for an item based on brand, title, serial number, keyword and/or publisher</li>

 <li>List current loans by a specific member</li>

 <li>List frequently loaned items for each semester</li>

 <li>List members who have loaned an item over a duration of time</li>

 <li>List new acquisitions made by staff or student members</li>

 <li>Fines report containing information about fines imposed and members fined</li>

 <li>Provide information about student member privileges</li>

 <li>Provide information about reservation dates of resources</li>

 <li>Provide information about the privilege’s members have</li>

 <li>Provide information about the maximum possible loans a student member can take out</li>

</ul>

Business Rules:

<ol>

 <li><strong>Expiration of Student Member Access</strong>

  <ul>

   <li>A student’s borrowing privileges are taken away when they finish their enrolled course.</li>

   <li>When the date is later than the end date, they are automatically taken away.</li>

   <li>The status of the student member is set to ‘disabled’</li>

  </ul></li>

 <li><strong>Maximum number of items loaned or reserved at any one time</strong>

  <ul>

   <li>A student member cannot borrow, or reserve more than the maximum number of items specified in his/her privileges at any given time</li>

   <li>Staff members have precedence over student members regarding loaning resources</li>

  </ul></li>

 <li><strong>Late returns by student member penalties</strong>

  <ul>

   <li>Each student member has a default set of points earned at the beginning of their course (12 to start with)</li>

   <li>For each incurred day that the item is overdue, a penalty of 3 points is given, which is deducted from the total amount that student member has</li>

   <li>When the points come to 0, member status of that student is disabled, and borrowing/reservation privileges are revoked</li>

  </ul></li>

 <li><strong>Cancellation of Reservations</strong>

  <ul>

   <li>A reserved item is cancelled if it is not collected by the member on the day of the required due date</li>

   <li>Non-cancellation of a reservation by a member means 1 point is deducted from the member’s total</li>

   <li>Administrators can also cancel any reservation as they hold the right to do so</li>

  </ul></li>

 <li><strong>Borrowing/Reservation Periods</strong>

  <ul>

   <li>The duration of the borrowing/reservation periods, being either number of days or hours, is determined by the category to which the item belongs</li>

  </ul></li>

</ol>







<strong>ENTITY TYPES:</strong>

<table>

 <tbody>

  <tr>

   <td width="174">Entity Name</td>

   <td width="174">Description</td>

   <td width="174">Aliases</td>

   <td width="174">Occurrence</td>

  </tr>

  <tr>

   <td width="174">Catalogue</td>

   <td width="174">A database of resources that is used to search for loanable items</td>

   <td width="174">Database</td>

   <td width="174">Online database where the catalogue can be accessed</td>

  </tr>

  <tr>

   <td width="174">Resources</td>

   <td width="174">Items both physical and virtual that are used by students to aide their study</td>

   <td width="174">Borrowed Items</td>

   <td width="174">Physically stored in certain locationsVirtually stored online</td>

  </tr>

  <tr>

   <td width="174">Category</td>

   <td width="174">Describes a group of items which are similar/the same</td>

   <td width="174"> </td>

   <td width="174">Items are categorized so searching for them and loaning is more efficient</td>

  </tr>

  <tr>

   <td width="174">Location</td>

   <td width="174">Place where resources are kept</td>

   <td width="174"> </td>

   <td width="174">The place, physically or virtually, where a resource is stored</td>

  </tr>

  <tr>

   <td width="174">Movable Resource</td>

   <td width="174">Resources such as cameras, speakers, etc.</td>

   <td width="174"> </td>

   <td width="174">Loaned out by members of SEEC, either students or staff</td>

  </tr>

  <tr>

   <td width="174">Non-movable Resource</td>

   <td width="174">Resources such as classrooms, studios, laboratories, etc.</td>

   <td width="174">Buildings/Rooms</td>

   <td width="174">Loaned out by members of SEEC, either students or staff</td>

  </tr>

  <tr>

   <td width="174">Loan</td>

   <td width="174">Borrowing an item/resource</td>

   <td width="174">Borrow</td>

   <td width="174">Items that are borrowed from SEEC</td>

  </tr>

  <tr>

   <td width="174">Course Offering</td>

   <td width="174">A course that is offered by the University</td>

   <td width="174">Class/Subject</td>

   <td width="174">Members can partake in a course that is offered</td>

  </tr>

  <tr>

   <td width="174">Reservation</td>

   <td width="174">Resources student and staff members request to loan</td>

   <td width="174"> </td>

   <td width="174">A member logs online and requests to loan a resource from SEEC</td>

  </tr>

  <tr>

   <td width="174">Member</td>

   <td width="174">A student or staff member</td>

   <td width="174">Students/staff</td>

   <td width="174">Members reserve resources</td>

  </tr>

  <tr>

   <td width="174">Student</td>

   <td width="174">Members that enrol into courses at the University</td>

   <td width="174">Members</td>

   <td width="174">Students make reservations to loan a resource</td>

  </tr>

  <tr>

   <td width="174">Staff</td>

   <td width="174">Members that teach courses at the University</td>

   <td width="174">Members</td>

   <td width="174">Staff make reservations to loan a resource</td>

  </tr>

  <tr>

   <td width="174">Acquisition</td>

   <td width="174">Requests made by members, so they have access to new/more resources</td>

   <td width="174"> </td>

   <td width="174">Members make acquisitions which is then accepted or denied by admin staff</td>

  </tr>

  <tr>

   <td width="174">Privilege</td>

   <td width="174">Freedom to loan a resource from the School of SEEC</td>

   <td width="174"> </td>

   <td width="174">Student members have privilege which allows them to loan items</td>

  </tr>

  <tr>

   <td width="174">Administrator</td>

   <td width="174">A member of staff who decides/organizes acquisition requests</td>

   <td width="174"> </td>

   <td width="174">Checks to see if new resources can be supplied to members</td>

  </tr>

 </tbody>

</table>

<strong>RELATIONSHIP TYPES:</strong>

<table>

 <tbody>

  <tr>

   <td width="139">Entity Name</td>

   <td width="139">Multiplicity</td>

   <td width="139">Relationship</td>

   <td width="139">Multiplicity</td>

   <td width="139">Entity Name</td>

  </tr>

  <tr>

   <td width="139">Category</td>

   <td width="139">1..1</td>

   <td width="139">ProvidesAccessTo</td>

   <td width="139">*..1</td>

   <td width="139">Location</td>

  </tr>

  <tr>

   <td width="139">Location</td>

   <td width="139">1..*</td>

   <td width="139">Holds</td>

   <td width="139">1..1</td>

   <td width="139">Movable Resource</td>

  </tr>

  <tr>

   <td width="139">Privilege</td>

   <td width="139">0..*</td>

   <td width="139">Has</td>

   <td width="139">1..1</td>

   <td width="139">Category</td>

  </tr>

  <tr>

   <td width="139">Resources</td>

   <td width="139">0..*</td>

   <td width="139">Requires</td>

   <td width="139">1..1</td>

   <td width="139">Location</td>

  </tr>

  <tr>

   <td width="139">Movable/Non-movable resource</td>

   <td width="139"> </td>

   <td width="139">{Mandatory, or}</td>

   <td width="139"> </td>

   <td width="139">Resources</td>

  </tr>

  <tr>

   <td width="139">Resources</td>

   <td width="139">*..1</td>

   <td width="139">BelongsTo</td>

   <td width="139">1..*</td>

   <td width="139">Loan</td>

  </tr>

  <tr>

   <td width="139">Members</td>

   <td width="139">1..*</td>

   <td width="139">Make</td>

   <td width="139">1..1</td>

   <td width="139">Reservations</td>

  </tr>

  <tr>

   <td width="139">Staff/Student</td>

   <td width="139"> </td>

   <td width="139">{Mandatory, or}</td>

   <td width="139"> </td>

   <td width="139">Members</td>

  </tr>

  <tr>

   <td width="139">Members</td>

   <td width="139">0..*</td>

   <td width="139">Requests</td>

   <td width="139">1..*</td>

   <td width="139">Acquisitions</td>

  </tr>

  <tr>

   <td width="139">Administrator</td>

   <td width="139">1..*</td>

   <td width="139">Accepts/Denies</td>

   <td width="139">1..*</td>

   <td width="139">Acquisitions</td>

  </tr>

  <tr>

   <td width="139">Student</td>

   <td width="139">1..1</td>

   <td width="139">Have</td>

   <td width="139">1..*</td>

   <td width="139">Privilege</td>

  </tr>

  <tr>

   <td width="139">Student</td>

   <td width="139">1..1</td>

   <td width="139">Is Given A</td>

   <td width="139">0..*</td>

   <td width="139">Course Offering</td>

  </tr>

  <tr>

   <td width="139">Privilege</td>

   <td width="139">0..*</td>

   <td width="139">Provides</td>

   <td width="139">0..*</td>

   <td width="139">Course Offering</td>

  </tr>

  <tr>

   <td width="139">Resources</td>

   <td width="139">1..1</td>

   <td width="139">Require</td>

   <td width="139">0..*</td>

   <td width="139">Reservations</td>

  </tr>

 </tbody>

</table>

<strong>ATTRIBUTE TYPES: </strong>

<table>

 <tbody>

  <tr>

   <td width="108">Entity Name</td>

   <td width="110">Attributes</td>

   <td width="129">Description</td>

   <td width="99">Data Type &amp; Length</td>

   <td width="53">Nulls</td>

   <td width="63">Multi-valued</td>

   <td width="69">Derived</td>

   <td width="67">Default</td>

  </tr>

  <tr>

   <td rowspan="3" width="108">Resource</td>

   <td width="110">Resource ID</td>

   <td width="129">ID of the resource</td>

   <td width="99">Char(5)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="110">Description</td>

   <td width="129">Describes the resource</td>

   <td width="99">Varchar(100)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="110">Status</td>

   <td width="129">Status of a resource being loaned</td>

   <td width="99">Varchar(30)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td rowspan="6" width="108">Course Offering</td>

   <td width="110">Offering ID</td>

   <td width="129">ID of the offering loan</td>

   <td width="99">Char(6)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="110">Name</td>

   <td width="129">Name of the loan</td>

   <td width="99">Varchar(50)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="110">Semester Offered</td>

   <td width="129">Semester that the loan is offered</td>

   <td width="99">Int</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="110">Year Offered</td>

   <td width="129">Year that the loan is offered</td>

   <td width="99">Char(4)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="110">Course Beginning Date</td>

   <td width="129">The date the course begins</td>

   <td width="99">Varchar(20)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="110">Course End Date</td>

   <td width="129">The date the course ends</td>

   <td width="99">Varchar(20)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>ATTRIBUTE TYPES (CONT.): </strong>

<table>

 <tbody>

  <tr>

   <td width="105">Entity Name</td>

   <td width="92">Attributes</td>

   <td width="92">Description</td>

   <td width="99">Data Type &amp; Length</td>

   <td width="74">Nulls</td>

   <td width="77">Multi-valued</td>

   <td width="80">Derived</td>

   <td width="79">Default</td>

  </tr>

  <tr>

   <td rowspan="9" width="105">Member</td>

   <td width="92">Member ID</td>

   <td width="92">ID of a member</td>

   <td width="99">Char(5)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Name</td>

   <td width="92">Name of member</td>

   <td width="99">Varchar(30)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Email</td>

   <td width="92">Email of member</td>

   <td width="99">Varchar(30)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Address</td>

   <td width="92">Address of member</td>

   <td width="99">Varchar(50)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">City</td>

   <td width="92">Status of member</td>

   <td width="99">Varchar(12)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">State</td>

   <td width="92">State of Member</td>

   <td width="99">Varchar(30)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Postcode</td>

   <td width="92">Postcode of Member</td>

   <td width="99">Char(4)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Phone Number</td>

   <td width="92">Phone number(s) of member</td>

   <td width="99">Char(10)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Comments</td>

   <td width="92">Comments about member</td>

   <td width="99">Varchar(100)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td rowspan="2" width="105">Student Member</td>

   <td width="92">Member ID</td>

   <td width="92">ID of Member</td>

   <td width="99">Char(5)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Penalty Points</td>

   <td width="92">Reservation points a student has</td>

   <td width="99">Int</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79">12</td>

  </tr>

  <tr>

   <td width="105">Staff Member</td>

   <td width="92">Member ID</td>

   <td width="92">ID of Member</td>

   <td width="99">Char(5)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td rowspan="6" width="105">Administrator</td>

   <td width="92">Admin ID</td>

   <td width="92">ID of Admin</td>

   <td width="99">Char(10)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Status</td>

   <td width="92">Status of the acquisition</td>

   <td width="99">Varchar(15)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Fund Code</td>

   <td width="92">Code of Fund</td>

   <td width="99">Char(5)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Vendor Code</td>

   <td width="92">Code of Vendor</td>

   <td width="99">Char(5)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Price</td>

   <td width="92">How much the resource costs</td>

   <td width="99">Varchar(7)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

  <tr>

   <td width="92">Notes</td>

   <td width="92">Extra notes about the new resource</td>

   <td width="99">Varchar(50)</td>

   <td width="74">No</td>

   <td width="77">No</td>

   <td width="80">No</td>

   <td width="79"> </td>

  </tr>

 </tbody>

</table>

<strong>ATTRIBUTE TYPES (CONT.):</strong>

<table>

 <tbody>

  <tr>

   <td width="103">Entity Name</td>

   <td width="131">Attributes</td>

   <td width="104">Description</td>

   <td width="99">Data Type &amp; Length</td>

   <td width="56">Nulls</td>

   <td width="65">Multi-valued</td>

   <td width="71">Derived</td>

   <td width="68">Default</td>

  </tr>

  <tr>

   <td rowspan="4" width="103">Category</td>

   <td width="131">Category Code</td>

   <td width="104">Code of the resource’s category</td>

   <td width="99">Char(5)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Name</td>

   <td width="104">Name of category</td>

   <td width="99">Varchar(30)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Description</td>

   <td width="104">Description of category</td>

   <td width="99">Varchar(100)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Time Allowed</td>

   <td width="104">Time a resource can be used</td>

   <td width="99">Varchar(10)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td rowspan="4" width="103">Location</td>

   <td width="131">Location ID</td>

   <td width="104">ID of location</td>

   <td width="99">Char(5)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Room</td>

   <td width="104">Room location</td>

   <td width="99">Char(3)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Building</td>

   <td width="104">Building location</td>

   <td width="99">Varchar(3)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Campus</td>

   <td width="104">Campus location</td>

   <td width="99">Varchar(20)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="103">Movable Resource</td>

   <td width="131">Resource ID</td>

   <td width="104">ID of Resource</td>

   <td width="99">Char(5)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="103">Immovable Resource</td>

   <td width="131">Resource ID</td>

   <td width="104">ID of Resource</td>

   <td width="99">Char(5)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td rowspan="6" width="103">Loan</td>

   <td width="131">Resource ID</td>

   <td width="104">ID of offering</td>

   <td width="99">Char(10)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Member ID</td>

   <td width="104">ID of member</td>

   <td width="99">Char(10)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Date Loaned</td>

   <td width="104">Date resource is loaned</td>

   <td width="99">Varchar(30)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Date Due</td>

   <td width="104">Date resource is due</td>

   <td width="99">Varchar(30)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Time Loaned</td>

   <td width="104">Time resource is loaned</td>

   <td width="99">Varchar(5)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

  <tr>

   <td width="131">Time Due</td>

   <td width="104">Time resource is due</td>

   <td width="99">Varchar(5)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68"> </td>

  </tr>

 </tbody>

</table>

<strong>                                        </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>ATTRIBUTE TYPES (CONT.): </strong>

<table>

 <tbody>

  <tr>

   <td width="102">Entity Name</td>

   <td width="129">Attributes</td>

   <td width="105">Description</td>

   <td width="107">Data Type &amp; Length</td>

   <td width="54">Nulls</td>

   <td width="64">Multi-valued</td>

   <td width="70">Derived</td>

   <td width="67">Default</td>

  </tr>

  <tr>

   <td rowspan="2" width="102">Enrolment</td>

   <td width="129">Offering ID</td>

   <td width="105">ID of Course Offering</td>

   <td width="107">Char(6)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Member ID</td>

   <td width="105">ID of Member enrolling</td>

   <td width="107">Char(5)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td rowspan="5" width="102">Privilege</td>

   <td width="129">Privilege ID</td>

   <td width="105">ID of Privilege a member has</td>

   <td width="107">Char(4)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Name</td>

   <td width="105">Name of privilege</td>

   <td width="107">Varchar(30)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Description</td>

   <td width="105">Description of privilege</td>

   <td width="107">Varchar(50)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129"> </td>

   <td width="105">What kind of privilege a student member has</td>

   <td width="107">Varchar(16)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Max Resources</td>

   <td width="105">Time allowed for a student to borrow/book a resource</td>

   <td width="107">Char(1)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td rowspan="9" width="102">Acquisition</td>

   <td width="129">Acquisition ID</td>

   <td width="105">ID of Acquisition</td>

   <td width="107">Char(5)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Acquisition Request</td>

   <td width="105">Requested Item</td>

   <td width="107">Varchar(30)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Item Name</td>

   <td width="105">Name of item</td>

   <td width="107">Varchar(30)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Make</td>

   <td width="105">Make of resource</td>

   <td width="107">Varchar(20)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Manufacturer</td>

   <td width="105">Manufacturer of resource</td>

   <td width="107">Varchar(20)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Model</td>

   <td width="105">Model of resource</td>

   <td width="107">Varchar(20)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Year</td>

   <td width="105">Age of resource</td>

   <td width="107">Char(4)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Item Description</td>

   <td width="105">Item description</td>

   <td width="107">Varchar(150)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

  <tr>

   <td width="129">Item Urgency</td>

   <td width="105">How much is the item needed</td>

   <td width="107">Varchar(12)</td>

   <td width="54">No</td>

   <td width="64">No</td>

   <td width="70">No</td>

   <td width="67"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Relational Model Mapped with EER:</strong>

<table>

 <tbody>

  <tr>

   <td width="697"><strong>Location(</strong><u>LocationID</u>, Room, Building, Campus<strong>)</strong><strong>Primary Key</strong> LocationID<strong>Normalisation (BCNF):</strong>Location(<u>LocationID</u>, Room, Building, Campus)</td>

  </tr>

  <tr>

   <td width="697"><strong>Category(</strong><u>CategoryCode</u>, Name, Description, TimeAllowed<strong>) </strong><strong>Primary Key </strong>CategoryCode<strong>Normalisation (BCNF):</strong>Category(<u>CategoryCode</u>, Name, Description, TimeAllowed)</td>

  </tr>

  <tr>

   <td width="697"><strong>Resource(</strong><u>ResourceID</u>, CategoryCode, LocationID, Name, Description, Status<strong>) </strong><strong>Primary Key </strong>ResourceID<strong>Foreign Key </strong>CategoryCode <strong>references </strong>Category(CategoryCode)ON UPDATE CASCADE, ON DELETE NO ACTION<strong>Foreign Key </strong>LocationID <strong>references </strong>Location(LocationID)ON UPDATE CASCADE, ON DELETE NO ACTION<strong>Normalisation (BCNF):</strong>Resource(<u>ResourceID</u>, CategoryCode, LocationID, Description, Status)</td>

  </tr>

  <tr>

   <td width="697"><strong>Acquisition(</strong><u>AcquisitionID</u>, MemberID, AcquisitionRequest, ItemName, Make, Manufacturer, Model, Year, ItemDescription, ItemUrgency<strong>) </strong><strong>Primary Key </strong>AcquisitionID<strong>Foreign Key </strong>MemberID <strong>references </strong>Member(MemberID)ON UPDATE CASCADE, ON DELETE NO ACTION<strong>Normalisation (BCNF):</strong>Acquisition(<u>AcquisitionID</u>, AcquisitionRequest, ItemName, ItemDescription, ItemUrgency)Item Name(<u>ItemName</u>, Make, Manufacturer, Model, Year)</td>

  </tr>

  <tr>

   <td width="697"><strong>Course Offering(</strong><u>OfferingID</u>, Name, SemesterOffered, YearOffered, StartDate, EndDate<strong>) </strong><strong>Primary Key </strong>Offering ID<strong>Normalisation (BCNF):</strong>Course Offering(<u>OfferingID</u>, <u>CourseID</u>, SemesterOffered, YearOffered, StartDate, End Date)Course(<u>CourseID</u>, Name)</td>

  </tr>

  <tr>

   <td width="697"><strong>Privilege(</strong><u>PrivilegeID</u>, Name, Description, CategoryCode, MaxResources<strong>)</strong><strong>Primary Key</strong> PrivilegeID<strong>Foreign Key </strong>CategoryCode <strong>references</strong> Category(CategoryCode)ON UPDATE CASCADE, ON DELETE NO ACTION<strong>Normalisation (BCNF):</strong>Privilege(<u>PrivilegeID</u>, Name, Description, Privilege Category, MaxResources)</td>

  </tr>

  <tr>

   <td width="697"><strong>Movable Resource(</strong><u>ResourceID</u>, Description, Status, Name, Make, Manufacturer, Model, Year, AssetValue<strong>)</strong><strong>Primary Key </strong>Resource ID<strong>Normalisation (BCNF):</strong>Movable Resource(<u>ResourceID</u>, Description, Status, Name, Model)Item(<u>Model</u>, Make, Manufacturer, Year, AssetValue)</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Relational Model Mapped with EER (CONT.):</strong>

<table>

 <tbody>

  <tr>

   <td width="697"><strong>Immovable Resource</strong> <strong>(</strong><u>ResourceID</u><strong>)</strong><strong>Primary Key </strong>ResourceID<strong>Normalisation (BCNF):</strong>Immovable Resource(<u>ResourceID</u>)</td>

  </tr>

  <tr>

   <td width="697"><strong>Loan(</strong><u>MemberID</u>, ResourceID, DateLoaned, TimeLoaned, DateDue, TimeDue<strong>)</strong><strong>Primary Key </strong>MemberID<strong>Foreign Key </strong>ResourceID <strong>references </strong>Resource(ResourceID)ON UPDATE CASCADE, ON DELETE NO ACTION<strong>Normalisation (BCNF):</strong>Loan(<u>MemberID</u>, ResourceID, DateLoaned, TimeLoaned)Member(<u>MemberID</u>)Date(<u>DateLoaned</u>, DateDue)Time(<u>TimeLoaned</u>, TimeDue)</td>

  </tr>

  <tr>

   <td width="697"><strong>Member(</strong><u>MemberID</u>, Name, Email, Address, City, State, Postcode, Status, PhoneNumber, Comments<strong>) </strong><strong>Primary Key </strong>MemberID<strong>Normalisation (BCNF):</strong>Member(<u>MemberID</u>, Name, Email, Address, City, State, Status, PhoneNumber, Comments)Address(<u>City</u>, <u>State</u>, Postcode)</td>

  </tr>

  <tr>

   <td width="697"><strong>StudentMember(­</strong><u>MemberID)</u><strong>Primary Key </strong>MemberID<strong>Foreign Key </strong>(MemberID)<strong> references </strong>Member(MemberID)ON UPDATE CASCADE, ON DELETE NO ACTION<strong>Normalisation (BCNF):               </strong>StudentMember(­<u>MemberID</u>)</td>

  </tr>

  <tr>

   <td width="697"><strong>StaffMember(­</strong><u>MemberID)</u><strong>Primary Key </strong>MemberID<strong>Foreign Key </strong>(MemberID)<strong> references </strong>Member(MemberID)ON UPDATE CASCADE, ON DELETE NO ACTION<strong>Normalisation (BCNF):</strong>StaffMember(­<u>MemberID</u>)</td>

  </tr>

  <tr>

   <td width="697"><strong>Administrator(</strong><u>AdminID</u>, Status, FundCode, VendorCode, Price, Notes<strong>)</strong><strong>Primary Key </strong>AdminID<strong>Normalisation (BCNF):</strong>Administrator(­­<u>AdminID</u>, Status, Notes, VendorCode)Vendor(<u>VendorCode</u>, Price, FundCode)</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>The Normalisation Process/Method:</strong>

<strong>Administrator(</strong><u>Admin ID</u>, Status, Fund Code, Vendor Code, Price, Notes<strong>)</strong>

<strong>Primary Key </strong>Admin ID

<strong>Normalisation:</strong>

R:<strong> Administrator(</strong><u>Admin ID</u>, Status, Fund Code, Vendor Code, Price, Notes<strong>)</strong>

<ul>

 <li>All the attributes inside of Administrator is known as R.</li>

</ul>

FD1: Administrator -&gt; ­­<u>Admin ID</u>, Status, Notes, Vendor Code

<ul>

 <li>This is the first functional dependency on R where Administrator is represented as X1 and everything on the right side of the arrow is represented as Y1.</li>

</ul>

FD2: Vendor Code -&gt; Price, Fund Code

<ul>

 <li>Vendor Code is known as a functional dependency. Without the vendor code, price and fund code wouldn’t exist. Vendor Code is represented as X2 and Price and Fund Code are represented as Y2 in FD2.</li>

</ul>

R-Y2: <u>Admin ID</u>, Status, Vendor Code, Notes

<ul>

 <li>Y2 is removed from R to decompose the functional dependency.</li>

</ul>

Vendor(<u>Vendor Code</u>, Price, Fund Code) -&gt; 3NF

<ul>

 <li>Vendor Code and Admin ID are now candidate keys</li>

</ul>

Administrator(­­<u>AdminID</u>, Status, Notes, VendorCode)

Vendor(<u>VendorCode</u>, Price, FundCode)

<ul>

 <li>The functional dependency is now in BCNF.</li>

</ul>

<strong>Member(</strong><u>Member ID</u>, Name, Email, Address, City, Postcode, Status, Phone Number, Comments Field<strong>) </strong><strong>Primary Key </strong>Student ID

<strong>Normalisation:</strong>

R= <strong>Member(</strong><u>Member ID</u>, Name, Email, Address, City, Postcode, Status, Phone Number, Comments Field<strong>) </strong>

<ul>

 <li>All the attributes inside of Member is known as R.</li>

</ul>

FD1: Member -&gt; <u>Member ID</u>, Name, Email, Address, City, Postcode, Status, Phone Number, Comments Field

<ul>

 <li>This is the first functional dependency on R where Student is represented as X1 and everything on the right side of the arrow is represented as Y1.</li>

</ul>

FD2: City, State -&gt; Postcode

<ul>

 <li>City and State are known as a functional dependency. Without them postcode wouldn’t exist. City and State is represented as X2 whilst Postcode is represented as Y2 in FD2.</li>

</ul>

R-Y2: <u>Member ID</u>, Name, Email, Address, City, State, Status, Phone Number, Comments Field

<ul>

 <li>Y2 is removed from R to decompose the functional dependency.</li>

</ul>

Postcode(<u>City</u>, <u>State</u>, Postcode) -&gt; BCNF

<ul>

 <li>The functional dependency is now in BCNF.</li>

</ul>