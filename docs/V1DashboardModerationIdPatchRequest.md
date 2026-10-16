# V1DashboardModerationIdPatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** |  | 
**Action** | Pointer to **string** |  | [optional] [default to "keep"]

## Methods

### NewV1DashboardModerationIdPatchRequest

`func NewV1DashboardModerationIdPatchRequest(status string, ) *V1DashboardModerationIdPatchRequest`

NewV1DashboardModerationIdPatchRequest instantiates a new V1DashboardModerationIdPatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DashboardModerationIdPatchRequestWithDefaults

`func NewV1DashboardModerationIdPatchRequestWithDefaults() *V1DashboardModerationIdPatchRequest`

NewV1DashboardModerationIdPatchRequestWithDefaults instantiates a new V1DashboardModerationIdPatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *V1DashboardModerationIdPatchRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1DashboardModerationIdPatchRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1DashboardModerationIdPatchRequest) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAction

`func (o *V1DashboardModerationIdPatchRequest) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *V1DashboardModerationIdPatchRequest) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *V1DashboardModerationIdPatchRequest) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *V1DashboardModerationIdPatchRequest) HasAction() bool`

HasAction returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


