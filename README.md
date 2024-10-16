# OpenAIo1ModelsTest

C# Repository that will:
* Use OpenAI o1 reasoning to compare 2 Microsoft 10-K SEC reports
  * 2023:  https://www.sec.gov/Archives/edgar/data/789019/000095017023035122/msft-20230630.htm#item_1a_risk_factors 
  * 2024:  https://www.sec.gov/Archives/edgar/data/789019/000095017024087843/msft-20240630.htm#item_1a_risk_factors 
* Extract the differences, changes in the "Strategic and Competitive Risks" section
* Use OpenAI GPT-4o-2024-08-06 to create a formatted Markdown table of risks
  * File Created: https://github.com/bartczernicki/OpenAIo1ModelsTest/blob/master/OpenAIo1ModelsTest/Output/MicrosoftRiskAnalysis.md  

TODO: Add all risk sections from SEC Report

Here is a comparison of the **"Strategic and Competitive Risks"** risk factors from Microsoft's 2023 and 2024 10K filings:  
| No. | Title                                                     | 2023 Summary                                                                                                                                                                                                                                                                             | 2024 Summary                                                                                                                                                                                                                                                                              | Change                                                                   |
|-----|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| 1   | Competition in the technology sector                      | Faced intense competition from companies ranging from large global firms with significant R&D resources to small specialized firms. Barriers to entry are low, markets evolve rapidly with changing technologies, and success depends on innovating appealing products, devices, and services. | Similar to 2023, highlighting intense competition from a range of competitors. Emphasizes the need to continue innovating and providing products, devices, and services that appeal to businesses and consumers to remain competitive.                                                     | Minor wording changes; emphasis remains the same                         |
| 2   | Competition among platform-based ecosystems               | Emphasized creating platform-based ecosystems with network effects among users, developers, and the platform provider. Faced significant competition from firms providing competing platforms, including vertically integrated models that may claim security and performance benefits.       | Similar to 2023, underscores challenges in competing with vertically integrated models. Highlighted competition in PC operating systems from new devices and form factors like smartphones and tablets. Emphasized importance of attracting developers and competing content marketplaces.      | Minor wording changes; emphasis remains the same                         |
| 3   | Business model competition                                | Competitors used various business models, including cloud-based services, investing in AI, offering free applications funded by advertising, and distributing open source software. These models could impact sales volumes, prices, and operating costs, potentially leading to lower margins.  | Similar to 2023, with additional emphasis on AI being a highly competitive and rapidly evolving market, and new competitors entering the market. Noted significant costs to build and support AI capabilities, and the need to respond to technological changes, regulatory developments, and scrutiny. | Modified to include increased emphasis on AI competition                 |
| 4   | Focus on cloud-based and AI services presents execution risks | Increasing focus on cloud-based services presented execution and competitive risks. Incurred costs to build and maintain cloud infrastructure, reducing operating margins. Success depended on executing in areas like compelling cloud experiences, compatibility, developer attraction, and reliability. | Focus on cloud-based and AI services presents execution and competitive risks. Incurring significant costs to build and maintain infrastructure for cloud computing and AI services, reducing operating margins. Success depends on execution in similar areas, with added emphasis on AI and rapid market evolution.               | Modified to include AI services; added risks regarding AI investments     |
| 5   | Risks associated with misuse of cloud-based and AI services     | Some users could engage in fraudulent or abusive activities through cloud-based services, such as unauthorized account use, credit card fraud, or violating terms of service. Efforts to detect and control such violations might not be effective, leading to adverse impacts on revenue or reputation.  | AI systems may be used in unintended or inappropriate ways. Users may engage in fraudulent or abusive activities through cloud-based services. Efforts to detect and control misuse may not be effective, potentially causing reputational damage or adverse impacts on business and results of operations.  | Modified to include AI misuse risks; added potential reputational damage |

Here is a comparison of the **"RISKS RELATING TO THE EVOLUTION OF OUR BUSINESS"** risk factors from Microsoft's 2023 and 2024 10K filings:  
| Row | Title                                                   | 2023 Summary                                                                                                                                                                                                                                                                                                                                                                                    | 2024 Summary                                                                                                                                                                                                                                                                                                                                                                                       | Change                                                                                                                                                                                                               |
|-----|---------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Intense competition across all markets                  | Microsoft faces intense competition across all markets for its products and services, which may lead to lower revenue or operating margins.                                                                                                                                                                                                                                                      | Microsoft faces intense competition across all markets for its products and services, which may adversely affect its results of operations.                                                                                                                                                                                                                                                         | Wording change in the last clause from "which may lead to lower revenue or operating margins" to "which may adversely affect our results of operations."                                                           |
| 2   | Competition in the technology sector                    | Competitors range from large global companies to small specialized firms; low barriers to entry; rapid evolution with changing technologies; need to innovate to remain competitive to avoid lower revenues or margins.                                                                                                                                                                           | Similar content, but with added emphasis: failure to innovate may adversely affect Microsoft's business, financial condition, and results of operations.                                                                                                                                                                                                                                            | Added emphasis on potential adverse effects on business, financial condition, and results of operations if Microsoft fails to innovate and remain competitive.                                                      |
| 3   | Competition among platform-based ecosystems             | Importance of creating platform-based ecosystems; competition from vertically-integrated models controlling software and hardware; challenges in attracting developers; risks associated with competing content and application marketplaces; potential increased costs and lower margins when shifting to vertically-integrated models or competing with low-cost platforms.                             | Similar content with minor wording changes; emphasizes the same risks, including competition from vertically-integrated models, challenges in attracting developers, and risks of competitors restricting Microsoft's ability to distribute products through their marketplaces.                                                                                                                   | Minor wording changes; no significant change in content.                                                                                                                     |
| 4   | Business model competition                              | Competition based on various business models: proprietary software licensing, free applications funded by advertising, and open source software; competitors may not bear the full costs of development; challenges from open source products mimicking Microsoft's features; transition to cloud-based models impacts revenue and margins.                                                         | Similar content but adds a new bullet point highlighting Microsoft's investment in AI across the company and infusion of generative AI capabilities into offerings; acknowledges AI as a highly competitive and rapidly evolving market; notes the need to be responsive to technological changes, regulatory developments, and public scrutiny in AI.                                              | Added discussion of investment in AI under "Business model competition"; recognizes AI as a significant competitive area and highlights associated risks.                                                          |
| 5   | Focus on cloud-based and AI services presents execution and competitive risks | Focus on cloud-based services presents execution and competitive risks; significant costs to build and maintain infrastructure; uncertainties in attracting users and generating required revenue; risks of decreased margins; need to execute in areas like bringing compelling experiences to market and ensuring reliability and security; potential user fraud and abuse impacting revenue or reputation. | Focus on cloud-based and AI services presents execution and competitive risks; significant costs to build and maintain infrastructure to support cloud computing and AI services; success depends on execution in several areas including AI; added emphasis on risks associated with misuse of AI systems and potential reputational damage; notes commitment to detect and control misuse but acknowledges efforts may not be effective. | Modified risk factor to explicitly include AI services; added risks related to AI, including misuse of AI systems, potential reputational damage, and the impact on business and results of operations.

Here is a comparison of the **"CYBERSECURITY, DATA PRIVACY, AND PLATFORM ABUSE RISKS"** risk factors from Microsoft's 2023 and 2024 10K filings:  
| No. | Title                                                           | 2023 Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 2024 Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Change                                                                                                                                                                                                                                                                                                      |
|-----|-----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Intense Competition Across All Markets                          | Present: "We face intense competition across all markets for our products and services, which may lead to lower revenue or operating margins."                                                                                                                                                                                                                                                                                                                                                                                              | Present: "We face intense competition across all markets for our products and services, which may adversely affect our results of operations."                                                                                                                                                                                                                                                                                                                                                                        | Modified wording; changed potential impact from "lower revenue or operating margins" to "adversely affect our results of operations."                                                                                                                                                                       |
| 2   | Competition in the Technology Sector                            | Present: Competitors range from global companies to small specialized firms; barriers to entry are low; rapid evolution with changing technologies; importance of innovation to remain competitive.                                                                                                                                                                                                                                                                                                                                        | Present: Similar content; added emphasis on innovation: "If we do not continue to innovate and provide products, devices, and services that appeal to businesses and consumers, we may not remain competitive, which may adversely affect our business, financial condition, and results of operations."                                                                                                                                                                                                               | Modified wording; added emphasis on the need to innovate to remain competitive; highlighted potential adverse effects.                                                                                                                                                                                       |
| 3   | Competition Among Platform-based Ecosystems                     | Present: Importance of creating platform-based ecosystems; beneficial network effects; necessity of achieving significant scale; facing competition from firms providing competing platforms.                                                                                                                                                                                                                                                                                                                                               | Present: Similar content; added concluding sentence: "For all of these reasons, we may not be able to compete successfully against our current and future competitors, which may adversely affect our business, operations, financial condition, and results of operations."                                                                                                                                                                                                                                            | Modified wording; added emphasis on potential inability to compete successfully and the adverse effects thereof.                                                                                                                                                                                             |
| 4   | Competing Vertically-integrated Models                          | Present: Competitors with vertically-integrated models control software and hardware; success in consumer products; potential to increase costs and reduce margins if we shift to this model.                                                                                                                                                                                                                                                                                                                                               | Present: Similar content; minor wording change: "Shifting a portion of our business to a vertically integrated model may increase our cost of revenue and reduce our operating margins."                                                                                                                                                                                                                                                                                                                            | Minor wording change; rephrased the impact of shifting to a vertically integrated model.                                                                                                                                                                                                                    |
| 5   | Competition in Operating Systems for PCs                        | Present: Significant competition from platforms for new devices like smartphones and tablets; devices compete on price and utility; users increasingly turn to these devices; difficulty attracting developers; competing with low-cost or free operating systems may decrease margins; some devices compete with OEM partners' products.                                                                                                                                                                                                 | Present: Similar content; minor wording changes: "Users continue to turn to these devices to perform functions that in the past were performed by PCs."                                                                                                                                                                                                                                                                                                                      | Minor wording changes; updated to reflect ongoing trend of users turning to alternative devices.                                                                                                                                                                                                            |
| 6   | Competition from Platforms with App Marketplaces                | Present: Competing platforms have content and application marketplaces with scale; importance of variety and utility of content; users may incur costs when switching platforms; need to enlist developers; efforts may increase costs and lower margins; competitors' marketplace rules may restrict distribution in accordance with our objectives.                                                                                                                                                                                      | Present: Similar content; no significant changes noted.                                                                                                                                                                                                                                                                                                                                                                                                                                                            | No significant changes.                                                                                                                                                                                                                                                                                     |
| 7   | Business Model Competition                                      | Present: Companies compete based on various business models, including cloud-based services, free applications funded by advertising, and modification/distribution of open source software; competitors may not bear full R&D costs; some open source products mimic our products.                                                                                                                                                                                                                                                        | Present: Similar content; continues to describe competition based on various business models, including cloud-based services, AI, free applications funded by advertising, and open source software; notes that we and our competitors are devoting significant resources to cloud-based strategies; mentions new competitors entering the AI market.                                                                                                                                                                   | Updated content; added emphasis on AI and the entry of new competitors in the AI market; slight reorganization of content.                                                                                                                                                                                  |
| 8   | Investment in Cloud-based Services                              | Present: Under "Our increasing focus on cloud-based services presents execution and competitive risks"; discusses significant resources devoted to cloud strategies; importance of execution in bringing compelling experiences to market; challenges in maintaining compatibility and performance across devices; need to enhance attractiveness to developers; ensuring reliability and security; making services platform-agnostic; uncertainty in attracting users and generating revenue; potential negative impact on margins and operating income. | Present: Content merged into "Business model competition" and "Our focus on cloud-based and AI services presents execution and competitive risks"; notes that "A material part of our business involves cloud-based services"; similar challenges and execution areas listed; added emphasis on AI; discusses significant costs to build and maintain infrastructure; potential adverse effects if revenue does not align with investments.                                                                                         | Modified organization; merged cloud services discussion with business model competition and execution risks; added AI to the focus areas; updated wording to reflect current strategies and challenges.                                                                                                       |
| 9   | Investment in AI                                                | Present: Investing in AI across the company; infusing AI capabilities into offerings; expectation that AI will be highly competitive and rapidly evolving; bearing significant development and operational costs; need to be responsive to technological change, regulatory developments, and public scrutiny.                                                                                                                                                                                                                             | Present: Similar content; updated to note that "new competitors continue to enter the market"; emphasizes significant costs to build and support AI models, services, platforms, and infrastructure; highlights the need to compete effectively amidst technological change, regulatory developments, and public scrutiny.                                                                                                                                                                                             | Emphasis increased on AI; updated content reflecting increased competition and costs; noted entry of new competitors in the AI market.                                                                                                                                                                       |
| 10  | License-based Proprietary Software Model                        | Present: The license-based proprietary software model generates substantial revenue; we bear R&D costs offset by licensing revenue; many competitors also develop and sell software under this model.                                                                                                                                                                                                                                                                                                                                      | Present: Similar content; continues to acknowledge that despite transitioning to cloud-based models, the proprietary software model remains a substantial source of revenue; competitors also employ this model.                                                                                                                                                                                                                                                             | No significant changes.                                                                                                                                                                                                                                                                                     |
| 11  | Competitors Offering Free Apps Funded by Advertising            | Present: Competitors offer free applications, services, and content funded by third-party advertising; these offerings compete directly with our revenue-generating products.                                                                                                                                                                                                                                                                                                                                                               | Present: Similar content; notes that advertising revenue funds development of products and services provided at little or no cost, competing directly with our products.                                                                                                                                                                                                                                                                                                    | No significant changes.                                                                                                                                                                                                                                                                                     |
| 12  | Competition from Open Source Software                           | Present: Some companies compete by modifying and distributing open source software at little or no cost; they may not bear full R&D costs; some open source products mimic our products' features and functionality.                                                                                                                                                                                                                                                                                                                       | Present: Similar content; continues to highlight competition from companies using open source software and AI models; notes that these firms may earn revenue on advertising or integrated products and services.                                                                                                                                                                                                                                                           | Modified wording; added reference to open source AI models; acknowledged that competitors may earn revenue on integrated products and services.                                                                                                                                                             |
| 13  | Execution Risks in Cloud-based and AI Services                  | Present: "Our increasing focus on cloud-based services presents execution and competitive risks"; lists areas of execution, including bringing compelling experiences to market, maintaining utility and performance across devices, enhancing attractiveness to developers, ensuring reliability and security, and making services platform-agnostic; uncertainty in attracting users and generating revenue; potential negative impact on margins and operating income.                                                            | Present: "Our focus on cloud-based and AI services presents execution and competitive risks"; similar list of execution areas; added emphasis on AI experiences and products; reiterates significant costs to build and maintain infrastructure; uncertainty in attracting users and generating revenue; potential adverse effects if revenue does not align with investments.                                                                                                     | Modified wording; added AI to focus areas in heading and content; updated execution areas to include AI experiences and products; reinforced the potential adverse effects if strategies do not succeed.                                                                                                    |
| 14  | Fraudulent or Abusive Activities in Cloud and AI Services       | Present: "Some users may engage in fraudulent or abusive activities through our cloud-based services"; includes unauthorized account use, stolen payment methods, failure to pay, terms of service violations; if efforts to detect and control are ineffective, may experience adverse revenue impacts or reputational damage.                                                                                                                                                                                                            | Present: Expanded to include AI systems: "Our AI systems offer users powerful tools and capabilities. However, there may be instances where these systems are used in ways that are unintended or inappropriate"; also notes continued risks of fraudulent or abusive activities in cloud services; acknowledges commitment to detect and control misuse; potential reputational damage or adverse impacts to business and results of operations if efforts are not effective.                                               | Expanded content to include risks from misuse of AI systems; updated wording to reflect potential unintended or inappropriate use of AI; reinforced commitment to detect and control misuse; emphasized possible reputational and operational impacts.                                                        |



