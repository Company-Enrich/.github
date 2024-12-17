# [CompanyEnrich](https://companyenrich.com)

[![API Status](https://img.shields.io/badge/API-Available-brightgreen)](https://companyenrich.com)

Welcome to **CompanyEnrich** – a powerful API that provides comprehensive company data to enhance your applications and services.

## 🚀 Company Enrichment API

**CompanyEnrich** offers detailed information about companies worldwide, allowing you to enrich your databases, improve customer insights, and make data-driven decisions.

### 🔑 Key Features

- **Extensive Company Data**: Access information on millions of companies globally.
- **Real-time Updates**: Receive the most current data available.
- **Easy Integration**: Simple RESTful API with straightforward endpoints.
- **Customizable Queries**: Retrieve only the data you need.
- **High Reliability**: Robust infrastructure ensuring maximum uptime.

## 🛠️ Getting Started

### Sign Up for an API Key

1. Visit [companyenrich.com](https://app.companyenrich.com) and create an account.
2. Navigate to your dashboard to obtain your unique API key.
3. Review the [API documentation](https://docs.companyenrich.com) to understand how to make requests.

### Making Your First API Call

Here’s how to make a simple API request to retrieve company information by domain:

#### Request

```http
GET https://api.companyenrich.com/companies/enrich?domain=example.com&api_key=YOUR_API_KEY
```

#### Example using `curl`

```bash
curl -X GET "https://api.companyenrich.com/companies/enrich?domain=example.com&api_key=YOUR_API_KEY" -H "Accept: application/json"
```

#### Response

```json
{
  "company": {
    "name": "Example Corp",
    "domain": "example.com",
    "logo": "https://assets.companyenrich.com/logos/example.png",
    "industry": "Information Technology",
    "size": "201-500",
    "founded": 2010,
    "description": "Example Corp is a leading provider of innovative solutions.",
    "address": {
      "street": "123 Example Street",
      "city": "Sample City",
      "state": "CA",
      "postal_code": "90001",
      "country": "USA"
    },
    "social_media": {
      "linkedin": "https://linkedin.com/company/example",
      "twitter": "https://twitter.com/example"
    }
  }
}
```

## 📚 API Documentation

Comprehensive documentation is available at [docs.companyenrich.com](https://companyenrich.com/docs). You'll find detailed information about:

- **Authentication**
- **Endpoints and Parameters**
- **Response Formats**
- **Error Handling**
- **Code Examples**

## 💡 Use Cases

- **Sales Intelligence**: Enhance your CRM with up-to-date company information.
- **Marketing Segmentation**: Improve targeting by enriching lead data.
- **Data Verification**: Validate and update company records in your database.
- **Analytics and Reporting**: Gain insights with comprehensive company profiles.

## 📝 Pricing

We offer flexible pricing plans to suit businesses of all sizes:

- **Free Tier**: Basic access with limited requests for testing and development.
- **Pro Tier**: Increased limits for growing businesses.
- **Enterprise Tier**: Custom solutions with dedicated support.

Learn more on our [Pricing Page](https://companyenrich.com/pricing).


## 📞 Support and Contact

Need assistance?

- **Email**: [support@companyenrich.com](mailto:support@companyenrich.com)
- **Live Chat**: Available on our [website](https://companyenrich.com).
- **FAQ**: [Frequently Asked Questions](https://companyenrich.com/pricing)

## 📢 Stay Updated

Follow us on social media to get the latest updates:

[![Twitter Follow](https://img.shields.io/twitter/follow/companyenrich?style=social)](https://twitter.com/companyenrich)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow-blue)](https://linkedin.com/company/companyenrich)
