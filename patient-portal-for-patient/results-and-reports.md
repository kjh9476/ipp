# Results and Reports

The Patient Portal menu allows the patient to view selected exams by the facility, including reports from ‘My Results’. Patients can communicate with appropriate staff in the facility regarding radiology results to request their own results by selecting ‘Request Result’.

## My Results

Patients can Review the patient's radiology test results and reports. Patient can do that regarding the results and reports which the facility allows the patient to view the result.

![](<../.gitbook/assets/image (15).png>)

### View Image

{% hint style="info" %}
**Info:** As access the result via ULite, the user account refers to the profile, “PATIENTPORTAL > ULITE\_ACCESS\_SHARED\_ID”
{% endhint %}

As clicking the View button, they can view their results via ULite like below;

![](<../.gitbook/assets/image (78).png>)

#### There is 3 mode to open ULite from patient portal.

* Default is embedded mode in the portal like above. (PATIENTPORTAL > ULITE\_EMBEDDED\_MODE = 0)
* Popup mode from the portal. There is no problem in security problem causing from cross-domain issue. (PATIENTPORTAL > ULITE\_EMBEDDED\_MODE = 1)
* Open ULite worklist mode for patient results just using portal for patient authentication. (PATIENTPORTAL > ULITE\_EMBEDDED\_MODE = 2)

{% hint style="warning" %}
**Note:** From Mobile (Tablet/Phone) environments, image view mode is working in popup mode regardless of the profile (PATIENTPORTAL > ULITE\_EMBEDDED\_MODE).
{% endhint %}

### View Report

If the patients click the Report button, they can view their reports like below;

![](<../.gitbook/assets/image (39).png>)

{% hint style="info" %}
**Info:** There is also an option to hold till showing the report button to access the result. As the profile PATIENTPORTAL > REPORT\_HOLD\_HOURS, the result shows up on the portal after the duration as report approval. This option works in “PATIENTPORTAL > ENABLE\_AUTO\_ISSUE = T” mode.
{% endhint %}

## Request result

This portal allows patients to request results and reports directly. Patient can request the results and reports which they were taken, and the request will be routed to the staffs’ message box.&#x20;

![](<../.gitbook/assets/image (2).png>)

1. Select the type of media such as Report Only or CD with images & Report.&#x20;
2. Select the way to get the result. If the patient selects ‘Pick up’ way, he/she can select the location to receive the result. \
   ![](<../.gitbook/assets/image (41).png>)
3. Select the studies to receive and also selects the exam date. \
   ![](<../.gitbook/assets/image (66).png>)
4. Enter the comments for this result request to let the staff know.&#x20;
5. Clicks the ‘Submit’ button to send the message to the staffs responsible for media management.

## Check requested result by staff

{% content-ref url="../portal-admin/message-box.md" %}
[message-box.md](../portal-admin/message-box.md)
{% endcontent-ref %}

## Issue result by staff manually

{% content-ref url="../portal-admin/portal-patients/result-issue-and-issued-key-management.md" %}
[result-issue-and-issued-key-management.md](../portal-admin/portal-patients/result-issue-and-issued-key-management.md)
{% endcontent-ref %}



