# Welcome
to an aggregation of documented GitHub security best practices and materials

#### General Material
* [Best Practices for Organizations](https://github.community/t/best-practices-for-organizations/10205) - Written by @pholleran
* [GitHub Enterprise Server Security Best Practices](https://www.youtube.com/watch?v=0MQihfI_OMA) - @mattcantstop at GitHub Universe 2015
* [Keeping Your Code Secure](https://www.youtube.com/watch?v=e01LOzSqDCI) - @shankuniyogi at GitHub Satellite 2019
* [Applying the GitHub security development lifecycle to your project](https://www.youtube.com/watch?v=R9JvD7hzJBg) - @jhutchings1 at GitHub Universe 2019

### Security on GitHub
#### You can think of GitHub Security as different buckets (so we can unravel what security our customers are talking about!)
   
 * Administrative Security - how do we secure our GitHub instance? how do we provision access to the right people? How do we keep malicious actors out?
    * Questions you may hear
       * Do you integrate with SAML SSO or Identity providers?
       * How do I give the correct people access to certain repositories?
       * How can I enforce an extra layer of authentication? Do you provide 2FA with TOTP or SMS?
 * Platform Security - How do we keep GitHub.com secure?
    * Questions you may hear
       * What compliances does your platform meet?
       * Are you FedRamp authorized? GDPR compliant?
 * Code Security - How do we secure your dependencies? How do we secure the code you and your teams write so that they're not introducing vulnerabilities?
     * Questions you may hear
        * Do you folks offer some kind of SCA (software composition analysis) tool (essentially alerts/updates/dependency insights)
        * Do you folks have code scanning solutions?
        * How do you keep my dependencies and code secure?
 * Data Leak Prevention - Tangential to administrative security, how do I enforce policies so that crucial code doesn't get leaked from my instances
     * Questions you may hear
        * How can I make sure that code doesn't enter public repositories on GitHub?
        * How can I make sure that users can't fork repos that are my IP?

