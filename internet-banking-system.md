The the above diagram is a [Container diagram](https://c4model.com/#ContainerDiagram), which is "zoom-in to the system boundary".

On this diagram only [API Application](api-application/index.html) is documented
and therefore has a page to which its diagram element links.

In the source diagram the "Mainframe Banking System" diagram element is linked to the "Mainframe Banking System" element on the [System Context Diagram](https://nasdanika-demos.github.io/internet-banking-system/index.html) using this element link: ``data:element/id,name,System+Context+Diagram/mainframe-banking-system``. 
As such, both elements link to the [Mainframe Banking System](../mainframe-banking-system/index.html) page in the generated site.

The "Internet Banking System" container is linked to the "Internet Banking System" node on the [System Context Diagram](../index.html) using this link: ``data:element/id,id,Ht1M8jgEwFfnCIfOTk4-/internet-banking-system``. 
This results in the "API Application" page being an immediate child of the "Internet Banking System" page.
Without it there would be an intermediate "Internet Banking System" label representing the container.

Another option to avoid an intermediate label where it is not desired is to use a regular node, not a container (container property is not checked).

