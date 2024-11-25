# 🔳 Ideal flow considering some available methods

The fundamental functions of an API include retrieving, sending, updating, and deleting information. This happens when a client or partner application sends a request to the ArqSign application, which in turn generates a response.

Below we show an ideal flow for implementing three of the available methods:

<figure><img src="../../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

**PHASE 01:** The client's application calls the [**POST/api/v2/processo/enviar-documento-para-assinar**](available-methods-in-the-api/1.-process/1.1.-post-api-v2-processo-enviar-documento-para-assinar.md) method to send a document for signing. With a successful response, the API will return the generated process ID, and you should store it to use this ID as a parameter in other methods.

**PHASE 02:** The client's application calls the [**GET/api/v1/processo/{idProcesso}/status-do-processo**](available-methods-in-the-api/1.-process/1.4.-get-api-v1-processo-idprocesso-status-do-processo.md) method to monitor the status of the process generated in Phase 01. It is recommended to call this method at most once a day; it is not necessary to call it constantly, as the status of a process will only be marked as completed after all signatories have signed the document.

**PHASE 03:** Once the process status is "Completed," you can move on to Phase 03, when you will call the [**GET/api/v2/processo/{idProcesso}**](available-methods-in-the-api/1.-process/1.2.get-api-v2-processo-idprocesso.md) method to retrieve the complete process data and the signed file.

