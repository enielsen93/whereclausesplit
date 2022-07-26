# whereclausesplit
 Python Package for splitting an arcpy SQL whereclause so length does not exceed allowed characters (3000)
 
<b>To install:</b>

```
python -m pip install https://github.com/enielsen93/whereclausesplit/tarball/master
```

## Example:
```
iterator = [u'O39060R', u'O39100R', u'O30114B', u'D16560R', u'O110_1', u'O30144B', u'O39900R', u'O30116R', u'O39270R', u'Node_153', u'Node_151', u'O30110R', u'O39651R', u'D16520R', u'O39130K', u'O39130R', u'O30112R', u'O39230R', u'O39653R', u'O39653Z', u'O39921R', u'O30040R', u'O39320R', u'O39112K', u'O39440R', u'O30084R', u'D16540R', u'O39280R', u'O39902R', u'O39050R', u'Node_78', u'O39110R', u'O39110K', u'O30082Z', u'F897', u'O39620R', u'O39904R', u'O39912R', u'D16280.2R', u'O30080W', u'O39340R', u'D16511R', u'F200_1', u'O39114K', u'O30022R', u'O30102R', u'O39908R', u'O30149R', u'O39410R', u'O18714C', u'D16513R', u'O30100R', u'O30020R', u'D16530R', u'O39140Z', u'O39203R', u'D16515R', u'O39600R', u'O39610R', u'O39201R', u'O39330R', u'O39903K', u'DU09', u'O109C_1', u'D16550R', u'O30141Z', u'O30010R', u'O39291R', u'O30145R', u'O39400R', u'O30115R', u'O39430R', u'O30030R', u'Node_148', u'Node_149', u'Node_145', u'Node_146', u'Node_147', u'O39150R', u'O39116K_2', u'O39090R', u'O39650R', u'O30143R', u'O39250R', u'O39905R', u'O30111R', u'O39652R', u'D16521R', u'O39420R', u'O30113C', u'O109A_1', u'O39113K', u'O30147R', u'O39901R', u'O30060R', u'O30085R', u'O39111K', u'O39906R', u'O39180R', u'O39903R']
where_clauses = splitWhereclause(iterator*100)
for where_clause in where_clauses:
    print((len(where_clause), where_clause))
```
