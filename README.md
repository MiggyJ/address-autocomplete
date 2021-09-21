# Address Autocomplete with PSGC API
https://miggyj.github.io/address-autocomplete/
## Description
This is a feature that ensures the correctness of a Philippine address. It uses the [API](psgc.gitlab.io/api) provided by the [Philippine Standard Geographic Code (PSGC)](https://psa.gov.ph/classification/psgc/). Select2 plugin is used for the select elements in this example.
## Storage
The main concern tackled in this feature is the storage of data. What this does is it saves the area code (instead of the area name) for each address section in the storage or database (region, province, municipality, and barangay) and utilizes a separate field for the full address which is composed of the area names for each section.
To check the data in this example, please visit the [Github Pages Site](https://miggyj.github.io/address-autocomplete/), fill up the form, and go to the `developer tools (F12) > Application > Local Storage > miggyj.github.io` and see each field or go to `developer tools (F12) > Console`.