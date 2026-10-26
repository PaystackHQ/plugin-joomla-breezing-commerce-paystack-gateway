
# Joomla Breezing Commerce Paystack Gateway

Welcome to the Joomla Breezing Commerce Paystack Gateway plugin repository on GitHub. 

Here you can browse the source code, look at open issues and keep track of development.

## Requirements

- PHP with the 21 Oct 2026 security fixes for critical remote code execution flaws (GHSA-w8hw-w9fx-j79w, GHSA-6wmf-4rv5-p3rp; [php.net advisory](https://www.php.net/releases/8_2_35.php)): **8.2.35, 8.3.36, 8.4.27, 8.5.12 or later**. PHP 8.1 and older no longer receive security fixes.
- Joomla and Breezing Commerce: this plugin is written for Joomla 3.x and Breezing Commerce (Crosstec) on Joomla 3. It uses APIs that were removed in Joomla 4 (`JRequest`, the `DS` constant, `JDatabase::query()`), so it will not run on Joomla 4 or 5 as it stands. Its PHP 8 warnings are fixed, and it has been linted and run against stubs on PHP 8.3 and 8.5 only, not on a real Joomla or Breezing Commerce install.
- Joomla 3.10 targets PHP 8.0 at most (the recommended version for 3.x), and community reports say it does not work on PHP 8.2 or later ([Joomla forum](https://forum.joomla.org/viewtopic.php?t=1002788), [Joomla Magazine](https://magazine.joomla.org/all-issues/december-2022/upgrading-your-site-to-php-8)). Joomla 4.4 (recommended PHP 8.2) and 5.x (recommended PHP 8.3) are the lines that can run PHP 8.2+ ([Joomla 5 requirements](https://manual.joomla.org/docs/5.4/get-started/technical-requirements/)), but we found no evidence that Breezing Commerce has been ported to Joomla 4 or 5 (see the [Crosstec forum](https://crosstec.org/en/forums/breezing-commerce-for-joomla/130813-joomla-4.html)). As far as we can establish, the Joomla 3 plus Breezing Commerce combination this plugin targets cannot run a patched PHP 8.2+. If you are on it, plan an upgrade to a platform that can run a patched PHP, and check with Crosstec about Breezing Commerce support first.


## Documentation

* [Paystack Documentation](https://developers.paystack.co/v2.0/docs/)
* [Paystack Helpdesk](https://paystack.com/help)

## Support

For bug reports and feature requests directly related to this plugin, please use the [issue tracker](https://github.com/PaystackHQ/plugin-joomla-breezing-commerce-paystack-gateway/issues). 

For general support or questions about your Paystack account, you can reach out by sending a message from [our website](https://paystack.com/contact).

## Community

If you are a developer, please join our Developer Community on [Slack](https://slack.paystack.com).

## Contributing to the Joomla Breezing Commerce Paystack Gateway plugin

If you have a patch or have stumbled upon an issue with the Joomla Breezing Commerce Paystack Gateway plugin, you can contribute this back to the code. Please read our [contributor guidelines](https://github.com/PaystackHQ/plugin-joomla-breezing-commerce-paystack-gateway/blob/master/CONTRIBUTING.md) for more information how you can do this.
