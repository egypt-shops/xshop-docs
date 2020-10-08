# XShop Documentation

Everything Documented about the XShop project.

- [Team members](./team_members.md)
- [The Project's Proposal](./project_proposal.md)
- [Tech Stack](tech_stack.md)
- [Software tools](software_tools.md)
- [High Level Design](./high_level_design.md)
- [Detailed Design](detailed_design)
  - [Web Pages](detailed_design/web_pages/)
    - [Home page](detailed_design/web_pages/home.md)
    - [Point of Sale](detailed_design/web_pages/pos.md)
    - [Data Entry](detailed_design/web_pages/data_entry.md)
    - [Admin Dashboard](detailed_design/web_pages/dashboard.md)
    - [Login](detailed_design/web_pages/login.md)
  - [API Endpoints](detailed_design/endpoints/)
    - [User Login](detailed_design/endpoints/login.md)
    - [User Logout](detailed_design/endpoints/logout.md)
  - [DB Models](detailed_design/db_models/)
    - [User](detailed_design/db_models/user.md)
    - [Customer](detailed_design/db_models/customer.md)
    - [Cashier](detailed_design/db_models/cashier.md)
    - [DataEntryClerk](detailed_design/db_models/data_entry_clerk.md)
    - [SubManager](detailed_design/db_models/sub_manager.md)
    - [Manager](detailed_design/db_models/manager.md)
    - [Shop](detailed_design/db_models/shop.md)
    - [PricingPlan](detailed_design/db_models/pricing_plan.md)
    - [Product](detailed_design/db_models/product.md)
    - [OrderItem](detailed_design/db_models/order_item.md)
    - [Order](detailed_design/db_models/order.md)
    - [Invoice](detailed_design/db_models/invoice.md)
  - [Mobile Screens](detailed_design/mobile_screens/)
    - [Home page](detailed_design/mobile_screens/home.md)

- [Research Notes](research_notes)
  - [The Marketplace](research_notes/marketplace.md)
  - [Order Fulfillment](research_notes/order_fulfillment.md)
  - [Pricing Plans](research_notes/pricing_plans.md)
  - [PWA offline](research_notes/pwa_offline.md)
  - [System Reports](research_notes/reports.md)
  - [Taxes](research_notes/taxes.md)
  - [Traceability Matrix](research_notes/traceability_matrix.md)

## How to contribute

- clone the repo / pull to get latest
- make sure you're on `develop` branch `$ git checkout develop`
- if you already have the repo, make sure you have latest updates `$ git pull origin develop`
- branch out `$ git checkout -b new_branch_name`
- write your text/code
- push to GitHub `$ git push origin new_branch_name`
  - if you push you'll find a link in the terminal, click on it to make a PR
- go to GitHub, the repo page, and make a PR (Google it if you don't know how.)
