---
name: Adyen
description: >-
  End-to-end payments, data, and financial management in a single solution. Meet
  the financial technology platform that helps you realize your ambitions
  faster.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/adyen.yml
created: 2023/11/13
modified: 2024/02/19
specificationVersion: '0.16'
tags: []
apis:
  - name: Adyen Accounting Notifications API
    description: >-
      Adyen sends notifications through webhooks to inform your system about
      incoming and outgoing transfers in your platform. You can use these
      webhooks to build your implementation. For example, you can use this
      information to update balances in your own dashboards or to keep track of
      incoming funds.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/
    baseURL: https://cal-test.adyen.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/
      - type: OpenAPI
        url: properties/accounting-notifications-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/accounting-notifications-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/accounting-notifications-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-accounting-notifications-api
  - name: Adyen Account API
    description: >-
      This API is used for the classic integration. If you are just starting
      your implementation, refer to our new integration guide instead. The
      Account API provides endpoints for managing account-related entities on
      your platform. These related entities include account holders, accounts,
      bank accounts, shareholders, and verification-related documents. The
      management operations include actions such as creation, retrieval,
      updating, and deletion of them.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/Account/6/overview
    baseURL: https://cal-test.adyen.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/Account/6/overview
      - type: OpenAPI
        url: properties/accounts-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/accounts-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/accounts-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-account-api
  - name: Adyen Authentication Webhooks API
    description: >-
      Adyen sends webhooks to inform your system about events related to
      cardholder authentication.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/development-resources/webhooks/
    baseURL: https://cal-test.adyen.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/development-resources/webhooks/
      - type: OpenAPI
        url: properties/authentication-webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/authentication-webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/authentication-webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-authentication-webhooks-api
  - name: Adyen Balance Control API
    description: >-
      The Balance Control API lets you transfer funds between merchant accounts
      that belong to the same legal entity and are under the same company
      account.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/BalanceControl/1/overview
    baseURL: https://cal-test.adyen.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/BalanceControl/1/overview
      - type: OpenAPI
        url: properties/balance-control-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/balance-control-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/balance-control-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-balance-control-api
  - name: Adyen BinLookup API
    description: >-
      The BIN Lookup API provides endpoints for retrieving information, such as
      cost estimates, and 3D Secure supported version based on a given BIN.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/BinLookup/52/overview
    baseURL: https://pal-test.adyen.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/BinLookup/52/overview
      - type: OpenAPI
        url: properties/binlookup-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/binlookup-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/binlookup-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-binlookup-api
  - name: Adyen Checkout API
    description: This is the description of your API.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/Checkout/71/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/Checkout/71/overview
      - type: OpenAPI
        url: properties/checkout-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/checkout-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/checkout-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-checkout-api
  - name: Adyen Configuration API
    description: >-
      The Configuration API enables you to create a platform where you can
      onboard your users as account holders and create balance accounts, cards,
      and business accounts.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/balanceplatform/2/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/balanceplatform/2/overview
      - type: OpenAPI
        url: properties/configuration-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/configuration-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/configuration-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-configuration-api
  - name: Adyen Configuration Webhooks API
    description: >-
      Adyen sends webhooks to inform your system about events that occur in your
      platform. These events include, for example, when an account holders
      capabilities are updated, or when a sweep configuration is created or
      updated. When an event occurs, Adyen makes an HTTP POST request to a URL
      on your server and includes the details of the event in the request body.
      You can use these webhooks to build your implementation.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview
      - type: OpenAPI
        url: properties/configuration-webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/configuration-webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/configuration-webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-configuration-webhooks-api
  - name: Adyen Data Protection API
    description: >-
      Adyen Data Protection API provides a way for you to process [Subject
      Erasure Requests](https://gdpr-info.eu/art-17-gdpr/) as mandated in GDPR.
      Use our API to submit a request to delete shopper''s data, including
      payment details and other related information (for example, delivery
      address or shopper email).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://gdpr-info.eu/art-17-gdpr/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://gdpr-info.eu/art-17-gdpr/
      - type: OpenAPI
        url: properties/data-protection-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/data-protection-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/data-protection-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-data-protection-api
  - name: Adyen Disputes API
    description: >-
      You can use the Disputes API to automate the dispute handling process so
      that you can respond to disputes and chargebacks as soon as they are
      initiated. The Disputes API lets you retrieve defense reasons, supply and
      delete defense documents, and accept or defend disputes.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/risk-management/disputes-api
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/risk-management/disputes-api
      - type: OpenAPI
        url: properties/disputes-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/disputes-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/disputes-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-disputes-api
  - name: Adyen Funds API
    description: >-
      The Fund API provides endpoints for managing the funds in the accounts on
      your platform. These management operations include, for example, the
      transfer of funds from one account to another, the payout of funds to an
      account holder, and the retrieval of balances in an account.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/
      - type: OpenAPI
        url: properties/funds-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/funds-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/funds-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-funds-api
  - name: Adyen Hosted Onboarding API
    description: >-
      The Fund API provides endpoints for managing the funds in the accounts on
      your platform. These management operations include, for example, the
      transfer of funds from one account to another, the payout of funds to an
      account holder, and the retrieval of balances in an account.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/
      - type: OpenAPI
        url: properties/hosted-onboarding-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/hosted-onboarding-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/hosted-onboarding-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-hosted-onboarding-api
  - name: Adyen Legal Entity API
    description: >-
      The Legal Entity Management API enables you to manage legal entities that
      contain information required for verification.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/
      - type: OpenAPI
        url: properties/legal-entity-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/legal-entity-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/legal-entity-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-legal-entity-api
  - name: Adyen Legal Entity API
    description: >-
      The Legal Entity Management API enables you to manage legal entities that
      contain information required for verification.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/
      - type: OpenAPI
        url: properties/legal-entity-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/legal-entity-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/legal-entity-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-legal-entity-api
  - name: Adyen Management API
    description: >-
      Configure and manage your Adyen company and merchant accounts, stores, and
      payment terminals.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/Management/3/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/Management/3/overview
      - type: OpenAPI
        url: properties/management-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/management-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/management-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-management-api
  - name: Adyen Management Webhooks API
    description: >-
      Adyen uses webhooks to inform your system about events that happen with
      your Adyen company and merchant accounts, stores, payment terminals, and
      payment methods when using [Management
      API](https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview).
      When a and includes the details of the event in the request body. See
      [Webhooks](https://docs.adyen.com/development-resources/webhooks) for more
      information.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview
      - type: OpenAPI
        url: properties/management-webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/management-webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/management-webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-management-webhooks-api
  - name: Adyen Notification Configuration API
    description: >-
      This API is used for the classic integration. If you are just starting
      your implementation, refer to our [new integration
      guide](https://docs.adyen.com/marketplaces-and-platforms) instead.\n\nThe
      Notification Configuration API provides endpoints for setting up and
      testing notifications that inform you of events on your platform, for
      example when a verification check or a payout has been completed.\n\nFor
      more information, refer to our
      [documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/marketplaces-and-platforms/classic/notifications
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/classic/notifications
      - type: OpenAPI
        url: properties/notification-configurations-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/notification-configurations-openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/notification-configurations-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-notification-configuration-api
  - name: Adyen Notification Webhooks API
    description: >-
      Adyen sends notifications through webhooks to inform your system about
      events that occur in the balance platform. These events include, for
      example, a card user making a payment, or a merchant starting a refund.
      When an event occurs, Adyen makes an HTTP POST request to a URL on your
      server and includes the details of the event in the request body. You can
      use the webhooks to build your implementation. For example, you can use
      this information to update balances in your own dashboards or to keep
      track of incoming funds.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/point-of-sale/design-your-integration/notifications/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/point-of-sale/design-your-integration/notifications/
      - type: OpenAPI
        url: properties/notification-webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/notification-webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/notification-webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-notification-webhooks-api
  - name: Adyen Notifications API
    description: >-
      The Notification API sends notifications to the endpoints specified in a
      given subscription. Subscriptions are managed through the Notification
      Configuration API. The API specifications listed here detail the format of
      each notification. For more information, refer to our
      [documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/marketplaces-and-platforms/classic/notifications
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/classic/notifications
      - type: OpenAPI
        url: properties/notifications-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/notifications-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/notifications-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-notifications-api
  - name: Adyen Payments API
    description: >-
      A set of API endpoints that allow you to initiate, settle, and modify
      payments on the Adyen payments platform. You can use the API to accept
      card payments (including One-Click and 3D Secure), bank transfers,
      ewallets, and many other payment methods.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/online-payments/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/online-payments/
      - type: OpenAPI
        url: properties/payments-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/payments-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/payments-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-payments-api
  - name: Adyen Payouts API
    description: >-
      A set of API endpoints that allow you to store payout details, confirm, or
      decline a payout.\n\nFor more information, refer to [Online
      payouts](https://docs.adyen.com/online-payments/online-payouts).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/online-payments/online-payouts
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/online-payments/online-payouts
      - type: OpenAPI
        url: properties/payouts-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/payouts-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/payouts-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-payouts-api
  - name: Adyen POS Terminal API
    description: >-
      This API provides endpoints for managing your point-of-sale (POS) payment
      terminals. You can use the API to obtain information about a specific
      terminal, retrieve overviews of your terminals and stores, and assign
      terminals to a merchant account or store.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/
      - type: OpenAPI
        url: properties/pos-terminal-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/pos-terminal-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/pos-terminal-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-pos-terminal-api
  - name: Adyen Recurring API
    description: >-
      The Recurring APIs allow you to manage and remove your tokens or saved
      payment details. Tokens should be created with validation during a payment
      request. For more information, refer to our [Tokenization
      documentation](https://docs.adyen.com/online-payments/tokenization).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/online-payments/tokenization
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/online-payments/tokenization
      - type: OpenAPI
        url: properties/recurring-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/recurring-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/recurring-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-recurring-api
  - name: Adyen Report Webhooks API
    description: >-
      Adyen sends webhooks to inform your system that reports were generated and
      are ready to be downloaded. You can download reports programmatically by
      making an HTTP GET request, or manually from your [Balance Platform
      Customer Area](https://balanceplatform-test.adyen.com/balanceplatform).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/report-webhooks/1/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/report-webhooks/1/overview
      - type: OpenAPI
        url: properties/report-webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/report-webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/report-webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-report-webhooks-api
  - name: Adyen Stored Value API
    description: A set of API endpoints to manage stored value products.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/
      - type: OpenAPI
        url: properties/stored-value-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/stored-value-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/stored-value-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-stored-value-api
  - name: Adyen Terminal API
    description: >-
      The Adyen Terminal API lets you make payments, issue refunds, collect
      shopper information, and perform other shopper-terminal interactions using
      a payment terminal supplied by Adyen.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/
      - type: OpenAPI
        url: properties/terminal-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/terminal-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/terminal-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-terminal-api
  - name: Adyen Test Cards API
    description: >-
      The Test Cards API provides endpoints for generating custom test card
      numbers. For more information, refer to [Custom test
      cards](https://docs.adyen.com/development-resources/testing/create-test-cards)
      documentation.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/development-resources/testing/create-test-cards
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/development-resources/testing/create-test-cards
      - type: OpenAPI
        url: properties/test-cards-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/test-cards-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/test-cards-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-test-cards-api
  - name: Adyen Transaction Webhooks API
    description: >-
      Adyen sends webhooks to inform your system about incoming and outgoing
      transfers in your platform. You can use these webhooks to build your
      implementation. For example, you can use this information to update
      balances in your own dashboards or to keep track of incoming funds.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/
      - type: OpenAPI
        url: properties/transaction-webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/transaction-webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/transaction-webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-transaction-webhooks-api
  - name: Adyen Transfer Webhooks API
    description: >-
      Adyen sends webhooks to inform your system about incoming and outgoing
      transfers in your platform. You can use these webhooks to build your
      implementation. For example, you can use this information to update
      balances in your own dashboards or to keep track of incoming funds.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview
      - type: OpenAPI
        url: properties/transfer-webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/transfer-webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/transfer-webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-transfer-webhooks-api
  - name: Adyen Transfers API
    description: >-
      This API provides endpoints that you can use to transfer funds, whether
      when [paying out to a transfer
      instrument](https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts),
      [sending funds to third
      parties](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/send-receive-funds)
      for users with business bank accounts, or to [request a payout for a grant
      offer](https://docs.adyen.com/marketplaces-and-platforms/capital). The API
      also supports use cases for [getting transactions for business bank
      accounts](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions-api)
      and getting [grants and its outstanding
      balances](https://docs.adyen.com/marketplaces-and-platforms/capital#get-balances).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: >-
      https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts
      - type: OpenAPI
        url: properties/transfers-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/transfers-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/transfers-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-transfers-api
  - name: Adyen Webhooks API
    description: >-
      We use webhooks to send you updates about payment status updates, newly
      available reports, and other events that you can subscribe to. For more
      information, refer to our
      [documentation](https://docs.adyen.com/development-resources/webhooks).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.adyen.com/development-resources/webhooks
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.adyen.com/development-resources/webhooks
      - type: OpenAPI
        url: properties/webhooks-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/webhooks-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/webhooks-openapi-api-evangelist-ratings.yml
    aid: adyen:adyen-webhooks-api
common:
  - type: Terms of Service
    url: https://www.adyen.com/legal/terms-and-conditions
  - type: Authentication
    url: https://www.adyen.com/authentication-3d-secure
  - type: Plans
    url: https://www.adyen.com/pricing
  - type: Documentation
    url: https://docs.adyen.com/
  - type: Newsletter
    url: https://www.adyen.com/newsletter
  - type: Knowledge
    url: https://www.adyen.com/knowledge-hub
  - type: Login
    url: https://authn-live.adyen.com/authn/ui/login
  - type: Support
    url: https://help.adyen.com/en_US
  - type: Contact
    url: https://help.adyen.com/en_US/contact
  - type: Webinars
    url: https://help.adyen.com/en_US/academy/webinars
  - type: Privacy
    url: https://www.adyen.com/policies-and-disclaimer/privacy-policy
  - type: OpenAPI
    url: https://github.com/Adyen/adyen-openapi
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
aid: adyen
---