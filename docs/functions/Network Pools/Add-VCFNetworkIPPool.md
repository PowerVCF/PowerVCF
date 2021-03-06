# Add-VCFNetworkIPPool

### Synopsis
Add an IP Pool to the Network of a Network Pool

### Syntax
```
Add-VCFNetworkIPPool -id <string> -networkid <string> -ipStart <string> -ipEnd <string>
```

### Description
The Add-VCFNetworkIPPool cmdlet connects to the specified SDDC Manager and adds a new IP Pool to an existing Network within a Network Pool.

### Examples
#### Example 1
```
Add-VCFNetworkIPPool -id 917bcf8f-93e8-4b84-9627-471899c05f52 -networkid c2197368-5b7c-4003-80e5-ff9d3caef795 -ipStart 192.168.110.61 -ipEnd 192.168.110.64
```
This example shows how create a new IP Pool on the existing network for a given Network Pool

### Parameters

#### -id
- ID of target Network Pool

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
```

#### -networkid
- ID of target IP Pool

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
```

#### -ipStart
- Start IP in the new range

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
```

#### -ipEnd
- End IP in the new range

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
```

### Notes

### Related Links
