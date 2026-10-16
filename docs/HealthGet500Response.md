# HealthGet500Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** |  | 
**Timestamp** | **string** |  | 
**Database** | **string** |  | 
**Error** | Pointer to **string** |  | [optional] 

## Methods

### NewHealthGet500Response

`func NewHealthGet500Response(status string, timestamp string, database string, ) *HealthGet500Response`

NewHealthGet500Response instantiates a new HealthGet500Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthGet500ResponseWithDefaults

`func NewHealthGet500ResponseWithDefaults() *HealthGet500Response`

NewHealthGet500ResponseWithDefaults instantiates a new HealthGet500Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *HealthGet500Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HealthGet500Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HealthGet500Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTimestamp

`func (o *HealthGet500Response) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *HealthGet500Response) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *HealthGet500Response) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetDatabase

`func (o *HealthGet500Response) GetDatabase() string`

GetDatabase returns the Database field if non-nil, zero value otherwise.

### GetDatabaseOk

`func (o *HealthGet500Response) GetDatabaseOk() (*string, bool)`

GetDatabaseOk returns a tuple with the Database field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabase

`func (o *HealthGet500Response) SetDatabase(v string)`

SetDatabase sets Database field to given value.


### GetError

`func (o *HealthGet500Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *HealthGet500Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *HealthGet500Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *HealthGet500Response) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


