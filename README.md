# RSS-GPT

[![](https://img.shields.io/github/last-commit/yinan-c/RSS-GPT/dev?label=updated)](https://github.com/yinan-c/RSS-GPT/tree/dev)
[![](https://img.shields.io/github/last-commit/yinan-c/RSS-GPT/main?label=feeds%20refreshed)](https://yinan-c.github.io/RSS-GPT/)
[![](https://img.shields.io/github/license/yinan-c/RSS-GPT)](https://github.com/yinan-c/RSS-GPT/blob/master/LICENSE)

## What is this?

Using GitHub Actions to run a simple Python script repeatedly: Calling OpenAI API to generate summaries for RSS feeds, and push the generated feeds to GitHub Pages. Easy to configure, no server needed.

### Features

- https://status.box.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/box.com.xml
- https://status.zapier.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/zapier.xml
- https://status.snyk.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/snyk.xml
- https://www.vercel-status.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Vercel.xml
- https://www.gocardless-status.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/GoCardless.xml
- https://status.clickhouse.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Clickhouse.xml
- https://status.sendgrid.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Sendgrid.xml
- https://status.mulesoft.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Mulesoft.xml
- https://status.hashicorp.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Hashicorp.xml
- https://status.openexchangerates.org/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Openexchangerates.xml
- https://status.heap.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Heap.xml
- https://status.supermetrics.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Supermetrics.xml
- https://status.bubble.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Bubble.xml
- https://status.asana.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Asana.xml
- https://status.monese.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Monese.xml
- https://status.dropbox.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Dropbox.xml
- https://status.octopus.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Octopus.xml
- https://status.etoro.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Etoro.xml
- https://status.twilio.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Twilio.xml
- https://status.alteryxcloud.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Alteryxcloud.xml
- https://status.klarna.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Klarna.xml
- https://status.thegoodtill.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Sumup.xml
- https://status.ngc.nvidia.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Nvdia.xml
- https://status.palantirfoundry.co.uk/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Palantir.xml
- https://status.slack.com/feed/rss -> https://jameslaneovermind.github.io/RSS-GPT/Slack.xml
- https://status.opentext.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/OpenText.xml
- https://status.1up.health/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/1upHealth.xml
- https://status.vanta.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Vanta.xml
- https://status.klarna.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Klarna.xml
- https://status.sumup.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/SumUp.xml
- https://status.hubspot.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/HubSpot.xml
- https://status.dazn.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/DAZN.xml
- https://status.zoom.us/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Zoom.xml
- https://status.wise.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Wise.xml
- https://status.permutive.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Permutive.xml
- https://status.razorpay.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Razorpay.xml
- https://status.hellosign.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/HelloSign.xml
- https://status.informatica.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Informatica.xml
- https://status.outrider.ai/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Outrider.xml
- https://status.thingsolver.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/ThingSolver.xml
- https://status.overwolf.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Overwolf.xml
- https://status.autodata-group.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Autodata Group.xml
- https://status.autogenai.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/AutoGenAI.xml
- https://status.airelogic.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Airelogic.xml
- https://status.platform9.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Platform9.xml
- https://status.aisera.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Aisera.xml
- https://status.redhat.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Red Hat.xml
- https://status.harness.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Harness.xml
- https://status.invicti.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Invicti.xml
- https://status.secondspectrum.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Second Spectrum.xml
- https://status.circleci.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/CircleCI.xml
- https://status.kandji.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Kandji.xml
- https://status.tricent.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Tricent.xml
- https://status.pendo.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Pendo.xml
- https://status.stormforge.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/StormForge.xml
- https://status.pagerduty.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/PagerDuty.xml
- https://status.securiti.ai/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Securiti.xml
- https://status.talkdesk.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Talkdesk.xml
- https://status.rockset.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Rockset.xml
- https://status.wix.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Wix.xml
- https://status.cloudsmith.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Cloudsmith.xml
- https://status.mongodb.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/MongoDB.xml
- https://status.greenphire.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Greenphire.xml
- https://status.lytx.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Lytx.xml
- https://status.benlabs.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Benlabs.xml
- https://status.schedulicity.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Schedulicity.xml
- https://status.sage.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Sage.xml
- https://status.sonos.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Sonos.xml
- https://status.jamf.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Jamf.xml
- https://status.typeform.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Typeform.xml
- https://status.ring.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Ring.xml
- https://status.calm.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Calm.xml
- https://status.tunein.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/TuneIn.xml
- https://status.dialogue.co/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Dialogue.xml
- https://status.observe.ai/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Observe.AI.xml
- https://status.iracing.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/iRacing.xml
- https://status.equityzen.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/EquityZen.xml
- https://status.virtuagym.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Virtuagym.xml
- https://status.weka.io/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Weka.IO.xml
- https://status.onfido.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Onfido.xml
- https://status.retraced.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Retraced.xml
- https://status.sonatype.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Sonatype.xml
- https://status.reltio.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Reltio.xml
- https://status.volteras.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Volteras.xml
- https://status.spreedly.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Spreedly.xml
- https://status.thanksben.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/ThanksBen.xml
- https://status.lunio.ai/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Lunio.xml
- https://status.snowflake.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Snowflake.xml
- https://status.fountain.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Fountain.xml
- https://status.robinhood.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Robinhood.xml
- https://status.shopify.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Shopify.xml
- https://status.aws.amazon.com/rss/all.rss -> https://jameslaneovermind.github.io/RSS-GPT/Amazon Web Services.xml
- https://status.slack.com/history.rss -> https://jameslaneovermind.github.io/RSS-GPT/Slack.xml
