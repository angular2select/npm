## beta
Angular 2 bootstrap select/multiselect directive module

http://angular2select.github.io/npm

```TypeScript

export interface ISelectConfig {
  actionsBox?: boolean;
  style?: string;
  size?: number;
  title?: string;
  liveSearch?: boolean;
  mobile?: boolean;
  multipleSeparator?: string;
  noneSelectedText?: string;
  selectedTextFormat?: string;
  showContent?: boolean;
  width?: string
}

```

```HTML

<select [(ngModel)]="selectedOptionId" multiple>
  <option *ngFor="let option of selectOptions" [value]="option.id">
    {{ option.name }}
  </option>
</select>

```
