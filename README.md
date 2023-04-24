# juanmaraujotraducciones-assets

## Games

- ### Game

  ```ts
  type Group = 'All' | 'Translation' | 'Proofreading' | 'LQA'
  ```

  | Property    | Type                                                  |
  | ----------- | ----------------------------------------------------- |
  | id          | number                                                |
  | name        | string                                                |
  | genres      | string[]                                              |
  | year        | string                                                |
  | image       | string                                                |
  | description | string                                                |
  | groups      | Group[]                                               |
  | words       | string                                                |
  | editor      | string                                                |
  | note        | string                                                |
  | order       | number                                                |

## Companies

- Company

  | Property | Type   |
  | -------- | ------ |
  | name     | string |
  | image    | string |

## Achievements

- ### Achievement

  | Property    | Type   |
  | ----------- | ------ |
  | title       | string |
  | description | string |
