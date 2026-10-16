# V1UserHistoryGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**[]V1UserHistoryGet200ResponseDataInner**](V1UserHistoryGet200ResponseDataInner.md) |  | 

## Methods

### NewV1UserHistoryGet200Response

`func NewV1UserHistoryGet200Response(success bool, data []V1UserHistoryGet200ResponseDataInner, ) *V1UserHistoryGet200Response`

NewV1UserHistoryGet200Response instantiates a new V1UserHistoryGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1UserHistoryGet200ResponseWithDefaults

`func NewV1UserHistoryGet200ResponseWithDefaults() *V1UserHistoryGet200Response`

NewV1UserHistoryGet200ResponseWithDefaults instantiates a new V1UserHistoryGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *V1UserHistoryGet200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *V1UserHistoryGet200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *V1UserHistoryGet200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *V1UserHistoryGet200Response) GetData() []V1UserHistoryGet200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *V1UserHistoryGet200Response) GetDataOk() (*[]V1UserHistoryGet200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *V1UserHistoryGet200Response) SetData(v []V1UserHistoryGet200ResponseDataInner)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


