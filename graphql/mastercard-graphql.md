# Mastercard GraphQL Schema

## Overview

Mastercard does not offer a native public GraphQL API. This conceptual GraphQL schema is derived from the Mastercard developer API surface area documented at [https://developer.mastercard.com/documentation](https://developer.mastercard.com/documentation). It covers the breadth of Mastercard's payment network capabilities including transaction processing, card management, fraud and risk, open banking, identity, and digital commerce.

## Source APIs

- Mastercard Transaction API
- Mastercard Authorization API
- Mastercard Clearing and Settlement API
- Mastercard Card Management API
- Mastercard Send (P2P and Remittance)
- Mastercard Simplify Commerce
- Mastercard Click to Pay / SRC (Secure Remote Commerce)
- Mastercard Decision Intelligence / Fraud Score
- Mastercard 3-D Secure (3DS)
- Mastercard Open Banking
- Mastercard Consumer Vault
- Mastercard Identity Services

## Schema File

See `mastercard-schema.graphql` for the full type definitions.

## Type Summary

| Category | Types |
|---|---|
| Transactions | Transaction, Authorization, Clearing, Settlement, TransactionStatus |
| Cards | Card, CardAccount, Cardholder, PaymentMethod |
| Tokens | Token, PaymentToken, ConnectedDeviceToken, ProcessorToken |
| Payments | SendPayment, SimplifyTransaction, P2P, RemittancePayment |
| FX | Currency, FXQuote, ConversionRate |
| 3DS | ThreeDS, ACS, Directory, Card3DSData |
| Click to Pay | SRCInitiator, ClickToPayProfile |
| Risk/Fraud | Risk, DecisionIntelligence, FraudScore, Security |
| Auth/Identity | Auth, Identity |
| Open Banking | OpenBanking, AccountInfo, BalanceInquiry, PaymentAccountRef |
| Services | ServiceProfile, ConsumerVault, Merchant, MerchantLocation |

## Reference

- Developer Portal: https://developer.mastercard.com/documentation
- GitHub: https://github.com/Mastercard
