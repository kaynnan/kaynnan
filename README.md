<div align="center">

# `kaynnan@github:~$ whoami`

### Kaynnan Bardauil Lemes

**Software Engineer · Odoo ERP Consultant · Open Source Contributor**

`Odoo` `Python` `PostgreSQL` `ERP` `OCA`

Building and maintaining ERP systems across **Brazil and Angola**.

[LinkedIn](https://www.linkedin.com/in/kaynnanbardauil) · [Email](mailto:kaynnanx1@gmail.com)

</div>

---

```console
$ cat /etc/profile

role        = Software Engineer / Odoo ERP Consultant
focus       = ERP engineering, integrations & business automation
stack       = Odoo · Python · PostgreSQL · XML · OWL
markets     = Brazil · Angola
opensource  = Odoo Community Association
company     = Founder @ Ark Solutions
```

## `$ cat about.md`

I work primarily with **Odoo ERP**, designing and implementing solutions around accounting, sales, purchasing, operations, localization and business automation.

My work ranges from business requirement analysis to backend development, module architecture, integrations, migrations and production troubleshooting.

A significant part of my engineering work is also contributed upstream to the **Odoo Community Association (OCA)**.

---

## `$ tree ~/engineering`

```text
engineering/
│
├── odoo/
│   ├── custom modules
│   ├── module architecture
│   ├── ORM & business logic
│   ├── XML / OWL
│   ├── migrations
│   └── localization
│
├── backend/
│   ├── Python
│   ├── PostgreSQL
│   ├── REST APIs
│   └── third-party integrations
│
├── erp/
│   ├── accounting
│   ├── sales & purchasing
│   ├── banking / CNAB
│   ├── analytic accounting
│   ├── repair & operations
│   └── business process automation
│
└── infrastructure/
    ├── Docker
    ├── Linux
    └── Git
```

## `$ git log --author="kaynnan" --oneline OCA/*`

I contribute **features, fixes, migrations and new modules** across multiple OCA repositories.

```text
l10n-brazil/
  FIX  Alphanumeric CNPJ dependency handling
  IMP  CNAB 240 banking structures
  IMP  Itaú / Sicoob / Santander / BB banking workflows
  ADD  DUIMP localization

repair/
  ADD  Repair analytic accounting
  ADD  Repair timesheet integration
  FIX  Analytic date & UoM propagation

accounting/
  ADD  Fiscal year closing ranges
  ADD  Payment term installments
  ADD  Advance compensation workflows

sales/
  ADD  Advanced blanket orders
  FIX  Quantity & UoM computation
  FIX  Loyalty program incompatibility

operations/
  IMP  Helpdesk / project synchronization
  ADD  Extended project states
  MIG  Multiple modules to Odoo 18
```

### `selected commits`

[`OCA/l10n-brazil#5009`](https://github.com/OCA/l10n-brazil/pull/5009)
**Alphanumeric CNPJ support**
Tracked a runtime validation failure to an outdated Python dependency and introduced the appropriate minimum version requirement with regression coverage.

[`OCA/l10n-brazil#4833`](https://github.com/OCA/l10n-brazil/pull/4833)
**Brazilian CNAB 240 banking**
Extended tax-payment structures and banking layouts across Sicoob, Santander, Itaú and Banco do Brasil.

[`OCA/repair#180`](https://github.com/OCA/repair/pull/180)
**Repair analytic accounting**
Fixed accounting-period and unit-of-measure inconsistencies when generating analytic lines from repair timesheets.

[`OCA/sale-promotion#359`](https://github.com/OCA/sale-promotion/pull/359)
**Loyalty program consistency**
Fixed an x2many synchronization issue that propagated incompatible promotion relationships between unrelated programs.

[`OCA/project#1586`](https://github.com/OCA/project/pull/1586)
**Project workflow extension**
Introduced additional project-state functionality as a reusable Odoo module.

[`OCA/account-closing#354`](https://github.com/OCA/account-closing/pull/354)
**Fiscal year closing**
Added range-based fiscal year closing functionality for more flexible accounting workflows.

> More contributions → [`github.com/pulls?q=author%3Akaynnan+org%3AOCA`](https://github.com/pulls?q=author%3Akaynnan+org%3AOCA)

---

## `$ cat ~/work.log`

```text
NOW   Ark Solutions
      Founder & Managing Partner
      ERP · Software Engineering · Business Solutions

      Escodoo / Brazil
      Odoo Development · Implementation · OCA

      TIS / Angola
      Odoo Development · Localization · Integrations
```

Beyond development, I work directly with stakeholders on **requirements analysis, solution design, technical decisions and ERP implementation**.

That combination lets me approach Odoo from both sides:

```text
business requirement
        ↓
process analysis
        ↓
solution design
        ↓
Odoo architecture
        ↓
implementation
        ↓
integration / automation
        ↓
production
```

---

## `$ printf "%s\n" "$CURRENT_FOCUS"`

```text
Odoo Development
ERP Implementation
ERP & Technical Consulting
Open Source Engineering
Business Process Automation
```

<div align="center">

---

`kaynnan@github:~$ █`

**Open to international Odoo, ERP and Software Engineering opportunities.**

[LinkedIn](https://www.linkedin.com/in/kaynnanbardauil) · [Email](mailto:kaynnanx1@gmail.com)

</div>
