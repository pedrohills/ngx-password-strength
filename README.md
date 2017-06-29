# forked from ngx-password-strength
A password strength component for Angular 2+

## Install

```
npm i -S https://github.com/pedrohills/ngx-password-strength.git
```


```
import { NgxPasswordStrengthModule } from 'ngx-password-strength/src';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    FormsModule,
    HttpModule,
    NgxPasswordStrengthModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

- How to use
```
<ngx-password-strength
  [checkPassword]="password"
  [colors]="['#EB1C24', '#F15A25', '#FA931D', '#F8B03A', '#37B54A']"
  [statusText]="['Very weak', 'Weak', 'Reasonable', 'Good', 'Strong']"></ngx-password-strength>
```

