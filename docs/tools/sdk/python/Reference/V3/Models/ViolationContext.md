---
id: violation-context
title: ViolationContext
pagination_label: ViolationContext
sidebar_label: ViolationContext
sidebar_class_name: pythonsdk
keywords: ['python', 'Python', 'sdk', 'ViolationContext', 'ViolationContext'] 
slug: /tools/sdk/python/v3/models/violation-context
tags: ['SDK', 'Software Development Kit', 'ViolationContext', 'ViolationContext']
---

# ViolationContext


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy** | [**ViolationContextPolicy**](violation-context-policy) |  | [optional] 
**conflicting_access_criteria** | [**ExceptionAccessCriteria**](exception-access-criteria) |  | [optional] 
}

## Example

```python
from sailpoint.v3.models.violation_context import ViolationContext

violation_context = ViolationContext(
policy=sailpoint.v3.models.violation_context_policy.ViolationContext_policy(
                    type = ENTITLEMENT, ),
conflicting_access_criteria=sailpoint.v3.models.exception_access_criteria.ExceptionAccessCriteria(
                    left_criteria = sailpoint.v3.models.exception_criteria.ExceptionCriteria(
                        criteria_list = [{type=ENTITLEMENT, id=2c9180866166b5b0016167c32ef31a66, existing=true}, {type=ENTITLEMENT, id=2c9180866166b5b0016167c32ef31a67, existing=false}], ), 
                    right_criteria = sailpoint.v3.models.exception_criteria.ExceptionCriteria(
                        criteria_list = [{type=ENTITLEMENT, id=2c9180866166b5b0016167c32ef31a66, existing=true}, {type=ENTITLEMENT, id=2c9180866166b5b0016167c32ef31a67, existing=false}], ), )
)

```
[[Back to top]](#) 

