<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Sales Email Generator</title>

<style>
body {
  font-family: Arial, sans-serif;
  background: #f4f6f8;
  padding: 40px;
}
h1 { text-align: center; }

.container {
  background: #fff;
  padding: 25px;
  max-width: 600px;
  margin: auto;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

label { display: block; margin-top: 15px; font-weight: bold; }

input, select {
  width: 100%;
  padding: 10px;
  margin-top: 5px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

button {
  margin-top: 15px;
  padding: 10px;
  width: 48%;
  border: none;
  background: #007bff;
  color: white;
  border-radius: 5px;
  cursor: pointer;
}

button:last-of-type { background: #28a745; }

pre {
  background: #1e1e1e;
  color: #00ff88;
  padding: 15px;
  margin-top: 20px;
  border-radius: 5px;
  white-space: pre-wrap;
}
</style>

</head>
<body>

<h1>📧 Sales Email Generator</h1>

<div class="container">

<label>Situation</label>
<select id="situation">
  <option value="first_contact">First Contact</option>
  <option value="follow_up">Follow-up</option>
  <option value="quotation">Quotation</option>
  <option value="delay">Delay Apology</option>
  <option value="complaint">Complaint Response</option>
</select>

<label>Tone</label>
<select id="tone">
  <option value="polite">Polite</option>
  <option value="direct">Direct</option>
</select>

<label>Company</label>
<input id="company" placeholder="ABC Company">

<label>Product</label>
<input id="product" placeholder="Your product">

<label>Deadline</label>
<input id="deadline" placeholder="April 10">

<button onclick="generateEmail()">Generate</button>
<button onclick="copyText()">Copy</button>

<pre id="result"></pre>

</div>

<script>
const templates = {

  follow_up: {
    polite: {
      subject: [
        "Just checking in regarding our previous email",
        "Gentle follow-up on {product}"
      ],
      body: `Dear {company},

I hope you are doing well.

I just wanted to follow up regarding {product}.
Please let me know if you had a chance to review it.

Looking forward to your feedback.

Best regards,`
    },
    direct: {
      subject: ["Follow-up on {product}"],
      body: `Hi {company},

Following up on {product}.
Please share your feedback.

Thanks.`
    }
  },

  first_contact: {
    polite: {
      subject: ["Introduction - {product}"],
      body: `Dear {company},

I hope this message finds you well.

We would like to introduce our {product}.
Please let us know if you are interested.

Best regards,`
    },
    direct: {
      subject: ["{product} proposal"],
      body: `Hi {company},

We offer {product}.
Let me know if you're interested.

Thanks.`
    }
  },

  quotation: {
    polite: {
      subject: ["Quotation for {product}"],
      body: `Dear {company},

Please find our quotation for {product} attached.

Kindly review and let us know your feedback.

Best regards,`
    },
    direct: {
      subject: ["Price for {product}"],
      body: `Hi {company},

Here is the price for {product}.
Please confirm.

Thanks.`
    }
  },

  delay: {
    polite: {
      subject: ["Update on delivery schedule"],
      body: `Dear {company},

We regret to inform you that the shipment of {product} will be delayed until {deadline}.

We sincerely apologize for any inconvenience caused.

Best regards,`
    },
    direct: {
      subject: ["Delay notice"],
      body: `Hi {company},

Shipment of {product} is delayed until {deadline}.

Apologies for the inconvenience.

Thanks.`
    }
  },

  complaint: {
    polite: {
      subject: ["Regarding your concern"],
      body: `Dear {company},

Thank you for bringing this issue to our attention.

We are currently reviewing the matter regarding {product} and will update you shortly.

Best regards,`
    },
    direct: {
      subject: ["Issue received"],
      body: `Hi {company},

We received your complaint regarding {product}.
We are checking and will update you.

Thanks.`
    }
  }

};

function generateEmail() {
  const situation = document.getElementById("situation").value;
  const tone = document.getElementById("tone").value;

  const company = document.getElementById("company").value || "your company";
  const product = document.getElementById("product").value || "the product";
  const deadline = document.getElementById("deadline").value || "the scheduled date";

  let template = templates[situation][tone];

  let subject = template.subject[Math.floor(Math.random() * template.subject.length)];
  let body = template.body;

  const replaceVars = (text) => {
    return text
      .replace(/{company}/g, company)
      .replace(/{product}/g, product)
      .replace(/{deadline}/g, deadline);
  };

  subject = replaceVars(subject);
  body = replaceVars(body);

  document.getElementById("result").innerText =
    "Subject: " + subject + "\\n\\n" + body;
}

function copyText() {
  const text = document.getElementById("result").innerText;
  navigator.clipboard.writeText(text);
  alert("Copied!");
}
</script>

</body>
</html>
