# Salesforce Integration Patterns

Here you will find different flavors of Salesforce integration approaches.

## Salesforce Trailmixes
(1) <a href="https://trailhead.salesforce.com/en/users/00550000006G25XAAS/trailmixes/integration-with-salesforce" target="_blank" alt="Integration with Salesforce">Integration with Salesforce</a><br/>

## Salesforce Integration Approaches
Salesforce integration approaches come in a number of different flavors. Here’s a high level overview.

<table>
	<tr>
		<th colspan="7">Salesforce Integration Approaches (High Level Overview)</th>
	</tr>
	<tr>
		<th>Declarative (Point and Click) / Programmatic</th>
		<th>Apex</th>
		<th>API</th>
		<th>Communication</th>
		<th>Protocol</th>
		<th>Data Format</th>
		<th>Details</th>
	</tr>
	<tr>
		<td>Declarative (Point and Click)</td>
		<td>Outbound Message</td>
		<td></td>
		<td>Asynchronous</td>
		<td>SOAP (WSDL)</td>
		<td>XML</td>
		<td></td>
	</tr>
	<tr>
		<td>Programmatic</td>
		<td>Apex @future callout methods</td>
		<td></td>
		<td>Asynchronous</td>
		<td></td>
		<td></td>
		<td>@future(callout=true)</td>
	</tr>
	<tr>
		<td>Programmatic</td>
		<td>Apex @webService keyword methods</td>
		<td>Custom SOAP API</td>
		<td>Synchronous</td>
		<td></td>
		<td></td>
		<td>call via Apex, Custom Buttons, AJAX Toolkit</td>
	</tr>
	<tr>
		<td>Programmatic</td>
		<td>Apex Inbound Email Service</td>
		<td></td>
		<td>Synchronous</td>
		<td></td>
		<td></td>
		<td>Messaging.InboundEmailHandler</td>
	</tr>
	<tr>
		<td>Programmatic</td>
		<td>Apex Outbound Email Service</td>
		<td></td>
		<td>Synchronous</td>
		<td></td>
		<td></td>
		<td>Messaging.SingleEmailMessage, Messaging.MassEmailMessage, Messaging.sendEmail()</td>
	</tr>
	<tr>
		<td>Programmatic</td>
		<td>Apex @RestResource annotation</td>
		<td>Apex REST API</td>
		<td>Synchronous</td>
		<td>REST</td>
		<td>JSON, XML, Custom</td>
		<td>Apex REST-based Web Services (@RestResource, @HttpDelete, @HttpGet, @HttpPut, @HttpPatch, @HttpPost)</td>
	</tr>
</table>


