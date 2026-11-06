---
layout: page
permalink: /opt-in/
title: SMS Opt-In & Study Registration
description: Participant Registration and SMS Consent for Zenith Lab Research
nav: false
---

# Study Participant Registration & SMS Opt-In

**ZENITH Lab &bull; Augusta University**  
*School of Computer & Cyber Sciences &bull; Department of Information Systems and Security*  
**Research Study Protocol:** IRB Protocol #2302261-1  
**Principal Investigator:** Dr. Gianluca Zanella (`gzanella64@gmail.com` &bull; `(706) 721-1110`)

---

### About the Study
Researchers at the ZENITH Lab at Augusta University are conducting academic research studies evaluating technology usability, interface interactions, and user decision-making in digital environments. Participants voluntarily sign up to attend study sessions and receive scheduling notifications, appointment reminders, and follow-up survey updates.

---

### Participant Registration & SMS Consent Form

<div class="card p-4 my-4 shadow-sm border" style="max-width: 650px; background-color: #fdfdfd;">
  <form onsubmit="event.preventDefault(); document.getElementById('opt-in-success').style.display='block';">
    
    <div class="form-group mb-3">
      <label for="full_name" class="font-weight-bold">Full Name:</label>
      <input type="text" id="full_name" class="form-control" placeholder="e.g. Jane Doe" required>
    </div>

    <div class="form-group mb-3">
      <label for="email_addr" class="font-weight-bold">Email Address:</label>
      <input type="email" id="email_addr" class="form-control" placeholder="e.g. jane.doe@example.com" required>
    </div>

    <div class="form-group mb-3">
      <label for="phone_number" class="font-weight-bold">Mobile Phone Number (US):</label>
      <input type="tel" id="phone_number" class="form-control" placeholder="+1 (555) 000-0000" pattern="[\+]?[0-9\s\-\(\)]+" required>
      <small class="form-text text-muted">Used solely to send your study session scheduling alerts and notifications.</small>
    </div>

    <!-- Carrier Mandated SMS Consent Checkbox (MUST BE UNCHECKED BY DEFAULT) -->
    <div class="form-check mb-4 p-3 border rounded" style="background-color: #f8f9fa;">
      <input type="checkbox" class="form-check-input" id="sms_consent_checkbox" required style="margin-top: 0.35rem;">
      <label class="form-check-label" for="sms_consent_checkbox" style="font-size: 0.92rem; line-height: 1.5; margin-left: 0.35rem;">
        <strong>I agree to receive SMS text notifications from Zenith Lab</strong> regarding research study sessions, appointment scheduling, and study updates at the mobile number provided above. 
        <br><br>
        &bull; <strong>Message frequency varies</strong> based on study schedule.<br>
        &bull; <strong>Message and data rates may apply.</strong><br>
        &bull; Text <strong>STOP</strong> to cancel at any time.<br>
        &bull; Text <strong>HELP</strong> for info and support.<br>
        &bull; Consent is voluntary and is not a condition of purchase or service.<br>
        &bull; View our <a href="/privacy/" target="_blank">Privacy Policy</a> and <a href="/terms/" target="_blank">Terms and Conditions</a>.
      </label>
    </div>

    <button type="submit" class="btn btn-primary btn-block py-2 font-weight-bold">
      Register & Consent to Study SMS Notifications
    </button>

    <div id="opt-in-success" class="alert alert-success mt-3" style="display: none;">
      Thank you! Your registration and consent for Zenith Lab study notifications have been received.
    </div>

  </form>
</div>

---

### Privacy & Carrier Compliance
ZENITH Lab is committed to protecting your data. 
- **No Mobile Information Sharing:** Mobile phone numbers and SMS opt-in consent data will **never** be shared, sold, or rented to any third parties or affiliates for marketing or promotional purposes under any circumstances.
- For complete details, review our full [Privacy Policy](/privacy/) and [Terms and Conditions](/terms/).
- **Support & Inquiries:** Contact Dr. Gianluca Zanella at `gzanella64@gmail.com` or call `+1 (706) 954-7441`.
