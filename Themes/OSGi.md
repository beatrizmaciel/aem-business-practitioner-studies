OSGi is a fundamental element in the technology stack of AEM. It is used to control the composite bundles of AEM and their configuration.

OSGi “provides the standardized primitives that allow applications to be constructed from small, reusable, and collaborative components. These components can be composed into an application and deployed”.

See [OSGi configuration settings](https://experienceleague.adobe.com/docs/experience-manager-65/content/implementing/deploying/configuring/osgi-configuration-settings.html?lang=en) for a list of the various bundles that are relevant to project implementation (listed according to bundle).

Each OSGi Component (see the OSGi Specification) is contained in one of the various bundles. When working with AEM, there are several methods of managing the configuration settings for such bundles

When working with AEM, there are several methods of managing the configuration settings for such services; see Configuring OSGi for more details and the recommended practices.

The following OSGi configuration settings (listed according to bundle) are relevant to project implementation:

*AEM Replication Event Listener Configure:*

The Run Modes, in which replication events are distributed to listeners. For example, if defined as author, it is the system that “initiates” the replication.

Add the run mode publish if the project code processes replication events (reverse replication) in a publish environment. For example, when the Dispatcher is used to flush from the publish environment or when standard replication to other publish instances occurs.

*AEM Repository change listener Configure:*

The Paths, locations to listen for repository events ready for distribution.
CRX Sling Client Repository Configure access to the underlying content repository.

The Admin Password should be changed after installation to ensure the security of your instance.
Other changes should not be necessary and care must be taken as they can affect access to the repository.
Apache Felix OSGi Management Console Configure:

Plugins, the main navigation items (console plugins) to be available in the Apache Felix Web Management Console as top-level menu items. Disable any you do not need as each requires space and resources.

*Apache Sling Customizable Request Data Logger Configure:*

Logger Name and Log Format to configure the location and format of request and access logging (default: request.log). This log file is essential when analyzing performance or debugging functionality related to the web chain. It is paired with the Apache Sling Request Logger.