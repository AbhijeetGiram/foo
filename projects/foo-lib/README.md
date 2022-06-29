# FooLib

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.1.0.

Demo: https://stackblitz.com/edit/foo-lib-demo

## Features

- Easy to integrate
- Supports every envionment

## Install

```
npm i foo-lib
```

## Setup

- Add FooLibModule to App NgModule

## Use

```bash
import { Component } from '@angular/core';
import { FooLibService } from 'foo-lib';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.scss']
})
export class AppComponent {

  constructor(
    private fooLibService: FooLibService
  ) { }

  ngOnInit(): void {
    this.fooLibService.test('Hello World!');
  }

}
```

## Upcoming features

- Custom foo
- UX design update for foo
- Backward compatibility with angular previous versions

## FAQ

Check out article on 
[Crash Course: Publish a Library on NPM](https://medium.com/@abhijeetgiram/ep-01-un-publish-npm-myths-8c8c3001fde9)

## License

HelloTest

---

> GitHub [@AbhijeetGiram](https://github.com/AbhijeetGiram) &nbsp;&middot;&nbsp;
> LinkedIn [@AbhijeetGiram](https://in.linkedin.com/in/abhijeet-giram-80265095) &nbsp;&middot;&nbsp;
> Medium [@AbhijeetGiram](https://medium.com/@abhijeetgiram)
