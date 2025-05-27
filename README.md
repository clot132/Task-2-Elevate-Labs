# Task-2-Elevate-Labs

---

## **Objective:**

Identify phishing characteristics in a suspicious email sample to understand how phishing emails can be detected through email header analysis and content inspection.

---

## **Tools Used:**

* **KnowBe Security Platform:** For generating a free phishing email test.
* **Email client:** To receive and view the phishing email including full headers.
* **MXToolbox Email Header Analyzer:** For analyzing the email header to verify SPF, DKIM, and DMARC authentication results.
* *(Optional)*: KnowBe’s phishing testing tools for email generation and security awareness.

---

## **Steps Performed:**

1. **Registered on KnowBe Security Platform**

   * Created an account on KnowBe to access free phishing email testing tools.
   * (Screenshot attached: *KnowBe_registration.png*)

2. **Launched Free Phishing Email Test**

   * After login, selected the “Free Phishing Email Test” option to generate a phishing simulation email.
   * (Screenshot attached: *Free_Security_Email_Phishingtest.png*)

3. **Received the Phishing Email Sample**

   * Checked email inbox and received the generated phishing email.
   * Saved the phishing email including full headers for analysis.
   * (Screenshot attached: *generated_phishingemail.png*)

4. **Copied the Email Header**

   * Opened the phishing email and extracted the complete email header text for verification.

5. **Analyzed the Email Header on MXToolbox**

   * Pasted the copied header into MXToolbox Email Header Analyzer. (https://mxtoolbox.com/EmailHeaders.aspx)
   * Reviewed authentication results for SPF, DKIM, and DMARC protocols.

6. **Reviewed Authentication Results:**

   * **DMARC:** Problem - Not compliant
   * **SPF Alignment:** Problem - Misaligned domain
   * **SPF Authentication:** OK - Passed SPF check, but alignment failed
   * **DKIM Alignment:** Problem - Misaligned domain
   * **DKIM Authentication:** Problem - Failed signature check

7. **Concluded Phishing Indicators**

   * Documented reasons why the email is suspicious and likely a phishing attempt.

---




