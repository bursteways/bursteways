# Architecture

## Prefer absolute imports

Importing using relative paths can get pretty ugly quickly. As your project grows in size, the importance of **organization** and **readability** starts to increase.

!!! danger Avoid
    ``` typescript
    import { VpcStack } from '../../../src/components/skeleton/index';
    ```

!!! success Prefer
    ``` typescript
    import { VpcStack } from 'components';
    ```


## Prefer named exports

## Prefer barrel pattern