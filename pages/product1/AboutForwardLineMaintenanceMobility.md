---
title: MM for Aviation Sample HTML to Markdown
keywords: sample
summary: "This is just a sample topic..."
sidebar: product1_sidebar
permalink: mm.html
folder: product1
---

::: {#page_content}
# Mobile Maintenance for Aviation

Mobile Maintenance for Aviation enables aviation maintenance teams to
perform maintenance activities from preparing for aircraft arrival,
recording maintenance, and deferring faults, to releasing an aircraft,
via the IFS Cloud Web and IFS Cloud Mobile user interfaces.

**IFS Cloud Mobile Maintenance for Aviation** consists of:

- The **Aviation Maintenance** web application for administrators to
  create and update reference and baseline data to support mobile
  maintenance activities.
- The **Mobile Maintenance for Aviation** mobile application**,** with
  App Store name **IFS Maintenance for Aviation,** available on mobile
  devices for aviation maintenance teams to record and execute work as
  it is performed with the ability to record some actions offline when a
  WiFi connectivity is lost. 
- The **Mobile Maintenance for Aviation** web application available for
  aviation maintenance teams to execute work via a web browser online.

 **IFS Cloud Mobile Maintenance for Aviation** can be deployed
integrated with Maintenix as the primary Maintenance and Engineering
(M&E) system, or as a standalone maintenance execution system.

## Setting up Basic Data and Requirements and Operational Data

Where options exist an administrator can choose to create or update
basic data and requirements (BDRs) for aviation maintenance workflows
via pages in **Aviation Maintenance/Basic Data** or choose to load data
via data loading and migration processes.  
  
Similarly in the case of aircraft configuration, an administrator can
load aircraft configuration data via data loading and migration
processes. Refer to the IFS Cloud Technical Documentation on Mobile
Maintenance for Aviation for information on how to migrate maintenance
data and load aircraft configuration.  
  
Line planners can upload work packages and their contents using the
Mobile Maintenance Work Package Loader. If Mobile Maintenance for
Aviation is not integrated with a flight following system, line
supervisors can create and update flights, as needed.  
  
Information is then ready to be utilized by mobile aviation maintenance
teams to perform maintenance activities.

## Activities Supported by the Mobile Maintenance for Aviation Applications

The Mobile Maintenance for Aviation applications enable mobile aviation
maintenance teams to handle the following maintenance activities that
occur until the aircraft is released as serviceable:

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<tbody>
<tr class="odd">
<td class="tablehead">Maintenance Activity</td>
<td class="tablehead">Description</td>
<td class="tablehead">Application Support</td>
<td class="tablehead">Offline and/or Online Support</td>
<td class="tablehead">Executable only when Mobile Maintenance for
Aviation is integrated with Maintenix</td>
</tr>
<tr class="even">
<td class="tableline">Review aircraft turns</td>
<td class="tableline">An aircraft turn is the time during which mobile
aviation maintenance occurs. For each aircraft turn, mobile aviation
maintenance teams can review the open, deferred and closed faults on the
aircraft and the contents of the work package scheduled during the
aircraft ground time.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online and offline</td>
<td class="tableline">No</td>
</tr>
<tr class="odd">
<td class="tableline">Assign resources</td>
<td class="tableline">Line supervisors can assign resources such as
technicians to tasks and turns and tools/equipment to tasks.</td>
<td class="tableline">Web application only</td>
<td class="tableline">Online only</td>
<td class="tableline">No</td>
</tr>
<tr class="even">
<td class="tableline">Raise and package faults</td>
<td class="tableline">New faults identified on an aircraft can be
recorded by a technician so they can be addressed. These faults, other
open faults and deferred faults which have not been assigned to a work
package can be packaged to a suitable work package.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online and offline</td>
<td class="tableline">No</td>
</tr>
<tr class="odd">
<td class="tableline">Add and view attachments on fault</td>
<td class="tableline">Line technicians and supervisors can add
attachments such as pictures, videos and documents to a fault. The
attachments can then be viewed and downloaded to help troubleshoot the
fault. <strong>Note</strong>: Adding attachments to tasks is not
supported.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Attachments can be added offline on a mobile
device. For another user to view attachments, the technician who
uploaded the attachment must have established a connection after adding
the attachment. To view an added attachment, you must be online.   </td>
<td class="tableline">No</td>
</tr>
<tr class="even">
<td class="tableline">Add parts, tools, skills and measurements to
task/fault requirements</td>
<td class="tableline">If all the required parts, tools, skills and
measurements needed to complete work on tasks or faults have not been
specified, a technician can add them prior to maintenance execution to
record their use and values during work capture.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online and offline</td>
<td class="tableline">No</td>
</tr>
<tr class="odd">
<td class="tableline">Find and reserve inventory</td>
<td class="tableline">Line technicians can find and reserve inventory in
Maintenix for part changes that must be carried out as a result of
performing maintenance on a task using the Mobile Maintenance for
Aviation applications.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online only</td>
<td class="tableline">Yes</td>
</tr>
<tr class="even">
<td class="tableline">Start work</td>
<td class="tableline">Line technicians can start work on task or fault,
to change the status of the task from Active to In Work.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online and offline</td>
<td class="tableline">No</td>
</tr>
<tr class="odd">
<td class="tableline">Initiate and receive remote assistance</td>
<td class="tableline">Line technicians can call experts or experts
groups and receive remote assistance using augmented video.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online only</td>
<td class="tableline">No</td>
</tr>
<tr class="even">
<td class="tableline">Record work</td>
<td class="tableline">Line technicians can record the status of steps,
actions taken, part changes, tool use and measurement values on work
tasks. They can also complete a task or close a fault.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online and offline. If you are recording usage for
tools/equipment that originate from IFS Cloud as opposed to Maintenix,
you must be online to do so.</td>
<td class="tableline">No</td>
</tr>
<tr class="odd">
<td class="tableline">Inspect work</td>
<td class="tableline">Line technicians or supervisors can inspect work
done by another technician and mark the status of steps that are
awaiting inspection as approved or rejected.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online and offline.</td>
<td class="tableline">No</td>
</tr>
<tr class="even">
<td class="tableline">Request deferral</td>
<td class="tableline">Line technicians can request to defer an open
fault which adds the fault to a list of faults to be deferred by a
maintenance operations controller (MOC).</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online only</td>
<td class="tableline">No</td>
</tr>
<tr class="odd">
<td class="tableline">Review fault to be deferred</td>
<td class="tableline">Maintenance operations controllers can review the
faults for which deferrals have been requested by line technicians.</td>
<td class="tableline">Web application</td>
<td class="tableline">Online only</td>
<td class="tableline">No</td>
</tr>
<tr class="even">
<td class="tableline">Initiate deferral</td>
<td class="tableline">Maintenance operations controllers can initiate
the deferral of a fault from the Mobile Maintenance for Aviation web
application. They can then authorize the deferral of the fault in
Maintenix, while providing the deferral authorization number to a
technician to defer the fault in Mobile Maintenance for Aviation. If
rejected, the technician must go on to fix the fault in Mobile
Maintenance for Aviation.</td>
<td class="tableline">Web application</td>
<td class="tableline">Online only</td>
<td class="tableline">Yes</td>
</tr>
<tr class="odd">
<td class="tableline">Mark fault as reviewed</td>
<td class="tableline">Once a fault has been reviewed, it can be marked
as reviewed by a maintenance operations controller, so it no longer
appears on the faults to be deferred list. It is then displayed in the
Reviewed Faults list.</td>
<td class="tableline">Web application</td>
<td class="tableline">Online only</td>
<td class="tableline">No</td>
</tr>
<tr class="even">
<td class="tableline">Defer faults</td>
<td class="tableline">Line technicians can defer open faults in a work
package, using deferral information as supplied by MOC, record deferral
actions, and sign for the deferral.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online and offline</td>
<td class="tableline">No</td>
</tr>
<tr class="odd">
<td class="tableline">Record and review fluid servicing</td>
<td class="tableline">Line technicians can record fluid uptakes which
line supervisors can then go on to review to monitor the rate of fluid
consumption.</td>
<td class="tableline">Record fluid servicing - Mobile and web
application<br />
Review fluid servicing - Web application only</td>
<td class="tableline">Record fluid servicing - online and offline<br />
Review fluid servicing - Web application only</td>
<td class="tableline">No</td>
</tr>
<tr class="even">
<td class="tableline">Review aircraft compliance and release aircraft to
service.</td>
<td class="tableline">Line technicians can view any open faults on the
aircraft and open tasks in the work package which prevent aircraft
release. They can also view if any configuration warnings have been
issued by the Configuration Management Service (CMS). Release an
aircraft to service provided no open faults or open tasks exist.
Complete the work package for the aircraft turn and update the status of
the turn to <strong>Released</strong>.</td>
<td class="tableline">Mobile and web application</td>
<td class="tableline">Online<span class="auto-style1">. A connection is
</span>required to release the aircraft to service.</td>
<td class="tableline">No. Yes to view configuration warnings by the
CMS.</td>
</tr>
</tbody>
</table>
:::

## Handling Failed Transactions

Failed transactions are transactions that do not synchronize with the
backend system for various reasons. The primary causes include system
data errors, transaction data errors, process errors, software errors,
or consequential errors.  
  
As a technician, if you encounter a banner alerting you of a failed
transaction or when you attempt to perform an activity like raising a
fault but find yourself unable to proceed further, you must reach out to
an administrator. The administrator will review the failed transaction
details and provide assistance in resolving the issue.  
  
If a failed transaction is present, banners are displayed on the
following pages:

- Aircraft Turn Details  
- Work Tasks  
- Open Faults  
- Deferred Faults  
- Closed Faults
- Fluid Servicing
- Task Details
- Task Steps
- Task Actions  
- Task Skills
- Task Measurements
- Task Tools Used
- Task Part Changes
- Task Faults Found  
- Fault Details
- Fault Actions
- Fault Skills
- Fault Part Changes  
- Fault Tools Used  
- Work Order  

**Note**: If you attempt to raise a fault from the dashboard when a
failed transaction has occurred, you will be notified of the failed
transaction when you click **Finish**.
