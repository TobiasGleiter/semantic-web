# 🔗 Linked Data: Connecting the Dots with URIs and RDF

**Linked Data** unlocks the potential of the Web by connecting information across different sources. This requires two key ingredients: URIs and RDF.

**What are URIs (Uniform Resource Identifiers)?**

Imagine them as unique addresses for anything on the web, not just websites. Just like your home address identifies your house, a URI precisely identifies a specific resource, be it a person, a product, a document, or even an abstract concept.

**URI Anatomy:**

- **Scheme:** Identifies the protocol (e.g., http, ftp).
- **Authority:** Optional for internal resources (e.g., [www.example.com](https://www.example.com)).
- **Path:** Specifies the location within the source (e.g., /articles/2024/linked-data).
- **Query:** (Optional) Filters information within the resource (e.g., ?author=john).
- **Fragment:** (Optional) Points to a specific part of the resource (e.g., #introduction).

**Beyond URLs:**

While URLs primarily address web pages, URIs encompass a broader range.

- URNs (Uniform Resource Names) identify resources without relying on internet access, and
- IRIs (Internationalized Resource Identifiers) allow for Unicode characters.

**Using URIs:**

Instead of using plain text labels, assign URIs to real-world entities like people, organizations, or products. This enables precise identification and linking across different datasets.

- `http://example.org/my_name`
- `http://example.org/bank_(creditinstitute)`
- `http://example.org/bank_(bench)`

---

## 🦆 References

1. J., Hladik, "Semantic Web", Duale Hochschule Baden-Württemberg, Stuttgart (fetched February 2024)

Optimized with [GEMINI](https://gemini.google.com/app)
