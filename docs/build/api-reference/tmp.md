# Usage

## Datasets

See `lumache.get_random_ingredients()` function


### lumache.get_random_ingredients(kind: List[str] | None = None)
Return a list of random ingredients as strings.


* **Parameters**

    **kind** (*list**[**str**] or **None*) – Optional “kind” of ingredients.



* **Raises**

    **lumache.InvalidKindError** – If the kind is invalid.



* **Returns**

    The ingredients list.



* **Return type**

    list[str]


See `lumache.InvalidKindError()`


### _exception_ lumache.InvalidKindError()
Raised if the kind is invalid.
