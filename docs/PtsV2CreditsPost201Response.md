# CyberSource.Model.PtsV2CreditsPost201Response
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | [**PtsV2PaymentsRefundPost201ResponseLinks**](PtsV2PaymentsRefundPost201ResponseLinks.md) |  | [optional] 
**Id** | **string** | An unique identification number assigned by CyberSource to identify the submitted request. | [optional] 
**SubmitTimeUtc** | **string** | Time of request in UTC. &#x60;Format: YYYY-MM-DDThh:mm:ssZ&#x60;  Example 2016-08-11T22:47:57Z equals August 11, 2016, at 22:47:57 (10:47:57 p.m.). The T separates the date and the time. The Z indicates UTC.  | [optional] 
**Status** | **string** | The status of the submitted transaction. | [optional] 
**ReconciliationId** | **string** | The reconciliation id for the submitted transaction. This value is not returned for all processors.  | [optional] 
**ClientReferenceInformation** | [**PtsV2PaymentsPost201ResponseClientReferenceInformation**](PtsV2PaymentsPost201ResponseClientReferenceInformation.md) |  | [optional] 
**CreditAmountDetails** | [**PtsV2CreditsPost201ResponseCreditAmountDetails**](PtsV2CreditsPost201ResponseCreditAmountDetails.md) |  | [optional] 
**ProcessorInformation** | [**PtsV2PaymentsRefundPost201ResponseProcessorInformation**](PtsV2PaymentsRefundPost201ResponseProcessorInformation.md) |  | [optional] 
**OrderInformation** | [**PtsV2PaymentsRefundPost201ResponseOrderInformation**](PtsV2PaymentsRefundPost201ResponseOrderInformation.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
