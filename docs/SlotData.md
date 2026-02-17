# SlotData

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the slot | [optional] 
**length** | **int** | Length of the Slot in frames. A Slot can have a length independant of the Shot in it. | [optional] 
**auto_length** | **bool** | By default a Slot adopts its length to the shots it contains. Once edited, the Slot length is maintained. | [optional] 
**shots** | [**list[ShotData]**](ShotData.md) |  | [optional] 
**smode** | **str** | Slot playmode in case the Slot length differs from the Shot length. | [optional] 
**timecode** | [**Timecode**](Timecode.md) |  | [optional] 
**transition** | [**SlotDataTransition**](SlotDataTransition.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

