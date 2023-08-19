# Hospital Catalog using ServiceNow
Welcome to Health Catalog, an innovative platform that empowers patients to take care of their health journey. Our user-friendly interface allows patients to easily schedule appointments tailored to their needs, choosing from a wide range of hospitals. Whether you prefer government or private facilities, our platform allows you to book appointments hassle-free, including services such as ambulances, blood banks, ICU wards, and emergency care.

# Technology and Stack used:
<ul>
  <li>Service Catalog</li>
  <li>Workflow</li>
  <li>Event and Notification</li>
  <li>Catalog Client Script</li>
  <li>Custom Table</li>
  <li>Form Validation</li>
  <li>UI Policy</li>
</ul>

# Major Steps of Hospital Catalog
<ul>
  <li>Registration and Check-in</li>
  <li>Hospital Approval</li>
  <li>Doctor Approval</li>
  <li>Waiting Area</li>
</ul>

# Custom Tables
<ul>
  <li><b>Doctor Table:</b></li> This table includes important information about the doctor, such as their name, specialty, phone number, date of hire, and the hospital they work at.
    <li>**Hospital Table:**</li> It contains information that includes the name and address of the hospital, the number of available beds and ICU wards, the hospital's phone number, and its type. 
</ul>

# Major Features
<ol>
  <li>
    **Auto Populate:** If a user picks a doctor's name from the custom table and also selects the hospital's name, the chosen doctor's phone number, specialty, and hospital name will fill in automatically. Furthermore, selecting a hospital will automatically fill in related fields like available wards, bed availability, contact number, and hospital address.
  </li>
  <li>
    **Form Validation for Fields:** Date of Birth, Registration Date and Time, Phone Number. 
  </li>
  <li>
  **Approval:** Users submit a form to the hospital, which is reviewed and approved if everything is in order. The form is then sent for a doctor's consultation, and the appointment is either accepted or rejected.
  </li>
  <li>**Email Notification:** The user received the email notification after approval or rejection of the appointment.
  </li>
</ol>
  
