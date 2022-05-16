# 1. Install
npm i hf-ui-controls

# 2. Get start
## import 
```js
import { UiControlsModule } from 'hf-ui-controls';
```
## component
### copy button

- data: User can type word
- copied: event, mean copy to clip board success. 

```hlml
<lib-copy-button [data]="title" (copied)="log()"></lib-copy-button>
```
