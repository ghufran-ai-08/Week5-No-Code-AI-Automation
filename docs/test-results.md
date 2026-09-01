# End-to-End Test Results

The AI Customer Support Automation was tested using three separate
Google Form submissions.

Each submission was processed through the complete workflow:

Google Form → Google Sheets → Make → Gemini → Gmail

---

## Test 1 — Technical Support

### Customer

Sarah Ahmed

### Input

The application crashes every time I try to upload a PDF. I have
restarted it several times but the problem continues.

### AI Category

Technical

### AI Urgency

High

### AI Summary

The customer is experiencing recurring application crashes whenever she attempts to upload a PDF, despite restarting the application multiple times.


### Email Delivery

PASS

---

## Test 2 — Billing

### Customer

Ali Khan

### Input

I was charged twice for the same subscription payment. Please help
me get one of the charges refunded.

### AI Category

Billing

### AI Urgency

High

### AI Summary

The customer was charged twice for the same subscription payment and is requesting a refund for the duplicate charge.


### Email Delivery

PASS

---

## Test 3 — Delivery

### Customer

Hamza Malik

### Input

My order was supposed to arrive yesterday but I still haven't
received it. Could you please check the delivery status?

### AI Category

Delivery

### AI Urgency

Medium

### AI Summary

The customer's order did not arrive on its expected delivery date yesterday, and they are requesting a status update on their shipment.


### Email Delivery

PASS

---

# Overall Result

3/3 end-to-end workflow tests completed successfully.

The workflow successfully:

1. Detected new Google Sheets rows.
2. Passed customer information to Gemini.
3. Generated an AI-powered support analysis.
4. Passed the AI result to Gmail.
5. Delivered the generated result by email.