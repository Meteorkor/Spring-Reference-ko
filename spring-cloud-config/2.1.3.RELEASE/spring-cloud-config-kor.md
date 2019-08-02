
* * * * *

**Table of Contents**

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#d0e9)

[1. Quick Start](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_quick_start)

[1.1. Client Side Usage](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_client_side_usage)

[2. Spring Cloud Config Server](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_spring_cloud_config_server)

[2.1. Environment Repository](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_environment_repository)

[2.1.1. Git Backend](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_git_backend)

[Skipping SSL Certificate Validation](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_skipping_ssl_certificate_validation)

[Setting HTTP Connection
Timeout](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_setting_http_connection_timeout)

[Placeholders in Git
URI](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_placeholders_in_git_uri)

[Pattern Matching and Multiple
Repositories](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_pattern_matching_and_multiple_repositories)

[Authentication](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_authentication)

[Authentication with AWS
CodeCommit](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_authentication_with_aws_codecommit)

[Git SSH configuration using
properties](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_git_ssh_configuration_using_properties)

[Placeholders in Git Search
Paths](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_placeholders_in_git_search_paths)

[Force pull in Git
Repositories](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_force_pull_in_git_repositories)

[Deleting untracked branches in Git
Repositories](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_deleting_untracked_branches_in_git_repositories)

[Git Refresh
Rate](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_git_refresh_rate)

[2.1.2. Version Control Backend Filesystem
Use](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_version_control_backend_filesystem_use)

[2.1.3. File System
Backend](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_file_system_backend)

[2.1.4. Vault
Backend](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#vault-backend)

[Multiple Properties
Sources](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_multiple_properties_sources)

[2.1.5. Accessing Backends Through a
Proxy](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_accessing_backends_through_a_proxy)

[2.1.6. Sharing Configuration With All Applications](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_sharing_configuration_with_all_applications)

[File Based Repositories](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#spring-cloud-config-server-file-based-repositories)

[Vault Server](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#spring-cloud-config-server-vault-server)

[2.1.7. JDBC Backend](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_jdbc_backend)

[2.1.8. CredHub Backend](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_credhub_backend)

[OAuth 2.0](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_oauth_2_0)

[2.1.9. Composite Environment Repositories](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#composite-environment-repositories)

[Custom Composite Environment Repositories](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_custom_composite_environment_repositories)

[2.1.10. Property Overrides](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_property_overrides)

[2.2. Health Indicator](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_health_indicator)

[2.3. Security](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_security)

[2.4. Encryption and Decryption](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_encryption_and_decryption)

[2.5. Key Management](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_key_management)

[2.6. Creating a Key Store for Testing](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_creating_a_key_store_for_testing)

[2.7. Using Multiple Keys and Key Rotation](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_using_multiple_keys_and_key_rotation)

[2.8. Serving Encrypted Properties](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_serving_encrypted_properties)

[3. Serving Alternative Formats](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_serving_alternative_formats)

[4. Serving Plain Text](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_serving_plain_text)

[5. Embedding the Config Server](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_embedding_the_config_server)

[6. Push Notifications and Spring Cloud Bus](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_push_notifications_and_spring_cloud_bus)

[7. Spring Cloud Config Client](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_spring_cloud_config_client)

[7.1. Config First Bootstrap](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#config-first-bootstrap)

[7.2. Discovery First Bootstrap](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#discovery-first-bootstrap)

[7.3. Config Client Fail Fast](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#config-client-fail-fast)

[7.4. Config Client Retry](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#config-client-retry)

[7.5. Locating Remote Configuration Resources](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_locating_remote_configuration_resources)

[7.6. Specifying Multiple Urls for the Config Server](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_specifying_multiple_urls_for_the_config_server)

[7.7. Configuring Timeouts](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_configuring_timeouts)

[7.8. Security](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_security_2)

[7.8.1. Health
Indicator](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_health_indicator_2)

[7.8.2. Providing A Custom
RestTemplate](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#custom-rest-template)

[7.8.3. Vault](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_vault)

[7.9. Nested Keys In Vault](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_nested_keys_in_vault)

**2.1.3.RELEASE**

Spring Cloud Config provides server-side and client-side support for
externalized configuration in a distributed system. With the Config
Server, you have a central place to manage external properties for
applications across all environments. The concepts on both client and
server map identically to the Spring `Environment`{.literal} and
`PropertySource`{.literal} abstractions, so they fit very well with
Spring applications but can be used with any application running in any
language. As an application moves through the deployment pipeline from
dev to test and into production, you can manage the configuration
between those environments and be certain that applications have
everything they need to run when they migrate. The default
implementation of the server storage backend uses git, so it easily
supports labelled versions of configuration environments as well as
being accessible to a wide range of tooling for managing the content. It
is easy to add alternative implementations and plug them in with Spring
configuration.

## Quick Start
퀵스타트에서는 Spring Cloud Config Server의 서버와 클라이언트를 사용합니다.

먼저, 아래와 같이 서버를 시작합니다.

``` {.screen}
$ cd spring-cloud-config-server
$ ../mvnw spring-boot:run
```

이 서버는 스프링 부트 어플리케이션이며, IDE를 통해서도 실행할 수 있습니다
(메인 클래스는`ConfigServerApplication` 입니다.)

클라이언트는 아래와 같이 호출합니다.
``` {.screen}
$ curl localhost:8888/foo/development
{"name":"foo","label":"master","propertySources":[
  {"name":"https://github.com/scratches/config-repo/foo-development.properties","source":{"bar":"spam"}},
  {"name":"https://github.com/scratches/config-repo/foo.properties","source":{"foo":"bar"}}
]}
```
property 찾는 기본 전략은 git 저장소를 복제하는 것입니다.
 (at `spring.cloud.config.server.git.uri`) 
 and use
it to initialize a mini `SpringApplication`{.literal}. The
mini-application’s `Environment`{.literal} is used to enumerate property
sources and publish them at a JSON endpoint.

The HTTP service has resources in the following form:

``` {.screen}
/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties
```

where `application`{.literal} is injected as the
`spring.config.name`{.literal} in the `SpringApplication`{.literal}
(what is normally `application`{.literal} in a regular Spring Boot app),
`profile`{.literal} is an active profile (or comma-separated list of
properties), and `label`{.literal} is an optional git label (defaults to
`master`{.literal}.)

Spring Cloud Config Server pulls configuration for remote clients from
various sources. The following example gets configuration from a git
repository (which must be provided), as shown in the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
```

Other sources are any JDBC compatible database, Subversion, Hashicorp
Vault, Credhub and local filesystems.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_client_side_usage)1.1 Client Side Usage {.title style="clear: both"}
---------------------------------------------------------------------------------------------------------------------------------------------------------

To use these features in an application, you can build it as a Spring
Boot application that depends on spring-cloud-config-client (for an
example, see the test cases for the config-client or the sample
application). The most convenient way to add the dependency is with a
Spring Boot starter
`org.springframework.cloud:spring-cloud-starter-config`{.literal}. There
is also a parent pom and BOM (`spring-cloud-starter-parent`{.literal})
for Maven users and a Spring IO version management properties file for
Gradle and Spring CLI users. The following example shows a typical Maven
configuration:

**pom.xml. **

``` {.programlisting}
   <parent>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-starter-parent</artifactId>
       <version>{spring-boot-docs-version}</version>
       <relativePath /> <!-- lookup parent from repository -->
   </parent>

<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>org.springframework.cloud</groupId>
            <artifactId>spring-cloud-dependencies</artifactId>
            <version>{spring-cloud-version}</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>

<dependencies>
    <dependency>
        <groupId>org.springframework.cloud</groupId>
        <artifactId>spring-cloud-starter-config</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
</dependencies>

<build>
    <plugins>
           <plugin>
               <groupId>org.springframework.boot</groupId>
               <artifactId>spring-boot-maven-plugin</artifactId>
           </plugin>
    </plugins>
</build>

   <!-- repositories also needed for snapshots and milestones -->
```

Now you can create a standard Spring Boot application, such as the
following HTTP server:

``` {.screen}
@SpringBootApplication
@RestController
public class Application {

    @RequestMapping("/")
    public String home() {
        return "Hello World!";
    }

    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }

}
```

When this HTTP server runs, it picks up the external configuration from
the default local config server (if it is running) on port 8888. To
modify the startup behavior, you can change the location of the config
server by using `bootstrap.properties`{.literal} (similar to
`application.properties`{.literal} but for the bootstrap phase of an
application context), as shown in the following example:

``` {.screen}
spring.cloud.config.uri: http://myconfigserver.com
```

By default, if no application name is set, `application`{.literal} will
be used. To modify the name, the following property can be added to the
`bootstrap.properties`{.literal} file:

``` {.screen}
spring.application.name: myapp
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

When setting the property `${spring.application.name}`{.literal} do not
prefix your app name with the reserved word `application-`{.literal} to
prevent issues resolving the correct property source.

The bootstrap properties show up in the `/env`{.literal} endpoint as a
high-priority property source, as shown in the following example.

``` {.screen}
$ curl localhost:8080/env
{
  "profiles":[],
  "configService:https://github.com/spring-cloud-samples/config-repo/bar.properties":{"foo":"bar"},
  "servletContextInitParams":{},
  "systemProperties":{...},
  ...
}
```

A property source called
``` ``configService:<URL of remote repository>/<file name> ```{.literal}
contains the `foo`{.literal} property with a value of `bar`{.literal}
and is highest priority.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The URL in the property source name is the git repository, not the
config server URL.

Spring Cloud Config Server provides an HTTP resource-based API for
external configuration (name-value pairs or equivalent YAML content).
The server is embeddable in a Spring Boot application, by using the
`@EnableConfigServer`{.literal} annotation. Consequently, the following
application is a config server:

**ConfigServer.java. **

``` {.programlisting}
@SpringBootApplication
@EnableConfigServer
public class ConfigServer {
  public static void main(String[] args) {
    SpringApplication.run(ConfigServer.class, args);
  }
}
```

Like all Spring Boot applications, it runs on port 8080 by default, but
you can switch it to the more conventional port 8888 in various ways.
The easiest, which also sets a default configuration repository, is by
launching it with `spring.config.name=configserver`{.literal} (there is
a `configserver.yml`{.literal} in the Config Server jar). Another is to
use your own `application.properties`{.literal}, as shown in the
following example:

**application.properties. **

``` {.programlisting}
server.port: 8888
spring.cloud.config.server.git.uri: file://${user.home}/config-repo
```

where `${user.home}/config-repo`{.literal} is a git repository
containing YAML and properties files.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

On Windows, you need an extra "/" in the file URL if it is absolute with
a drive prefix (for
example,`file:///${user.home}/config-repo`{.literal}).

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

The following listing shows a recipe for creating the git repository in
the preceding example:

``` {.screen}
$ cd $HOME
$ mkdir config-repo
$ cd config-repo
$ git init .
$ echo info.foo: bar > application.properties
$ git add -A .
$ git commit -m "Add application.properties"
```

![[Warning]](./Spring%20Cloud%20Config_files/warning.png)

Warning

Using the local filesystem for your git repository is intended for
testing only. You should use a server to host your configuration
repositories in production.

![[Warning]](./Spring%20Cloud%20Config_files/warning.png)

Warning

The initial clone of your configuration repository can be quick and
efficient if you keep only text files in it. If you store binary files,
especially large ones, you may experience delays on the first request
for configuration or encounter out of memory errors in the server.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_environment_repository)2.1 Environment Repository {.title style="clear: both"}
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

Where should you store the configuration data for the Config Server? The
strategy that governs this behaviour is the
`EnvironmentRepository`{.literal}, serving `Environment`{.literal}
objects. This `Environment`{.literal} is a shallow copy of the domain
from the Spring `Environment`{.literal} (including
`propertySources`{.literal} as the main feature). The
`Environment`{.literal} resources are parametrized by three variables:

-   `{application}`{.literal}, which maps to
    `spring.application.name`{.literal} on the client side.
-   `{profile}`{.literal}, which maps to
    `spring.profiles.active`{.literal} on the client (comma-separated
    list).
-   `{label}`{.literal}, which is a server side feature labelling a
    "versioned" set of config files.

Repository implementations generally behave like a Spring Boot
application, loading configuration files from a
`spring.config.name`{.literal} equal to the `{application}`{.literal}
parameter, and `spring.profiles.active`{.literal} equal to the
`{profiles}`{.literal} parameter. Precedence rules for profiles are also
the same as in a regular Spring Boot application: Active profiles take
precedence over defaults, and, if there are multiple profiles, the last
one wins (similar to adding entries to a `Map`{.literal}).

The following sample client application has this bootstrap
configuration:

**bootstrap.yml. **

``` {.programlisting}
spring:
  application:
    name: foo
  profiles:
    active: dev,mysql
```

(As usual with a Spring Boot application, these properties could also be
set by environment variables or command line arguments).

If the repository is file-based, the server creates an
`Environment`{.literal} from `application.yml`{.literal} (shared between
all clients) and `foo.yml`{.literal} (with `foo.yml`{.literal} taking
precedence). If the YAML files have documents inside them that point to
Spring profiles, those are applied with higher precedence (in order of
the profiles listed). If there are profile-specific YAML (or properties)
files, these are also applied with higher precedence than the defaults.
Higher precedence translates to a `PropertySource`{.literal} listed
earlier in the `Environment`{.literal}. (These same rules apply in a
standalone Spring Boot application.)

You can set spring.cloud.config.server.accept-empty to false so that
Server would return a HTTP 404 status, if the application is not
found.By default, this flag is set to true.

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_git_backend)2.1.1 Git Backend {.title}

The default implementation of `EnvironmentRepository`{.literal} uses a
Git backend, which is very convenient for managing upgrades and physical
environments and for auditing changes. To change the location of the
repository, you can set the
`spring.cloud.config.server.git.uri`{.literal} configuration property in
the Config Server (for example in `application.yml`{.literal}). If you
set it with a `file:`{.literal} prefix, it should work from a local
repository so that you can get started quickly and easily without a
server. However, in that case, the server operates directly on the local
repository without cloning it (it does not matter if it is not bare
because the Config Server never makes changes to the "remote"
repository). To scale the Config Server up and make it highly available,
you need to have all instances of the server pointing to the same
repository, so only a shared file system would work. Even in that case,
it is better to use the `ssh:`{.literal} protocol for a shared
filesystem repository, so that the server can clone it and use a local
working copy as a cache.

This repository implementation maps the `{label}`{.literal} parameter of
the HTTP resource to a git label (commit id, branch name, or tag). If
the git branch or tag name contains a slash (`/`{.literal}), then the
label in the HTTP URL should instead be specified with the special
string `(_)`{.literal} (to avoid ambiguity with other URL paths). For
example, if the label is `foo/bar`{.literal}, replacing the slash would
result in the following label: `foo(_)bar`{.literal}. The inclusion of
the special string `(_)`{.literal} can also be applied to the
`{application}`{.literal} parameter. If you use a command-line client
such as curl, be careful with the brackets in the URL — you should
escape them from the shell with single quotes ('').

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_skipping_ssl_certificate_validation)Skipping SSL Certificate Validation {.title}

The configuration server’s validation of the Git server’s SSL
certificate can be disabled by setting the
`git.skipSslValidation`{.literal} property to `true`{.literal} (default
is `false`{.literal}).

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://example.com/my/repo
          skipSslValidation: true
```

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_setting_http_connection_timeout)Setting HTTP Connection Timeout {.title}

You can configure the time, in seconds, that the configuration server
will wait to acquire an HTTP connection. Use the `git.timeout`{.literal}
property.

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://example.com/my/repo
          timeout: 4
```

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_placeholders_in_git_uri)Placeholders in Git URI {.title}

Spring Cloud Config Server supports a git repository URL with
placeholders for the `{application}`{.literal} and `{profile}`{.literal}
(and `{label}`{.literal} if you need it, but remember that the label is
applied as a git label anyway). So you can support a “one repository per
application” policy by using a structure similar to the following:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/myorg/{application}
```

You can also support a “one repository per profile” policy by using a
similar pattern but with `{profile}`{.literal}.

Additionally, using the special string "(\_)" within your
`{application}`{.literal} parameters can enable support for multiple
organizations, as shown in the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/{application}
```

where `{application}`{.literal} is provided at request time in the
following format: `organization(_)application`{.literal}.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_pattern_matching_and_multiple_repositories)Pattern Matching and Multiple Repositories {.title}

Spring Cloud Config also includes support for more complex requirements
with pattern matching on the application and profile name. The pattern
format is a comma-separated list of `{application}/{profile}`{.literal}
names with wildcards (note that a pattern beginning with a wildcard may
need to be quoted), as shown in the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          repos:
            simple: https://github.com/simple/config-repo
            special:
              pattern: special*/dev*,*special*/dev*
              uri: https://github.com/special/config-repo
            local:
              pattern: local*
              uri: file:/home/configsvc/config-repo
```

If `{application}/{profile}`{.literal} does not match any of the
patterns, it uses the default URI defined under
`spring.cloud.config.server.git.uri`{.literal}. In the above example,
for the “simple” repository, the pattern is `simple/*`{.literal} (it
only matches one application named `simple`{.literal} in all profiles).
The “local” repository matches all application names beginning with
`local`{.literal} in all profiles (the `/*`{.literal} suffix is added
automatically to any pattern that does not have a profile matcher).

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The “one-liner” short cut used in the “simple” example can be used only
if the only property to be set is the URI. If you need to set anything
else (credentials, pattern, and so on) you need to use the full form.

The `pattern`{.literal} property in the repo is actually an array, so
you can use a YAML array (or `[0]`{.literal}, `[1]`{.literal}, etc.
suffixes in properties files) to bind to multiple patterns. You may need
to do so if you are going to run apps with multiple profiles, as shown
in the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          repos:
            development:
              pattern:
                - '*/development'
                - '*/staging'
              uri: https://github.com/development/config-repo
            staging:
              pattern:
                - '*/qa'
                - '*/production'
              uri: https://github.com/staging/config-repo
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

Spring Cloud guesses that a pattern containing a profile that does not
end in `*`{.literal} implies that you actually want to match a list of
profiles starting with this pattern (so `*/staging`{.literal} is a
shortcut for `["*/staging", "*/staging,*"]`{.literal}, and so on). This
is common where, for instance, you need to run applications in the
“development” profile locally but also the “cloud” profile remotely.

Every repository can also optionally store config files in
sub-directories, and patterns to search for those directories can be
specified as `searchPaths`{.literal}. The following example shows a
config file at the top level:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          searchPaths: foo,bar*
```

In the preceding example, the server searches for config files in the
top level and in the `foo/`{.literal} sub-directory and also any
sub-directory whose name begins with `bar`{.literal}.

By default, the server clones remote repositories when configuration is
first requested. The server can be configured to clone the repositories
at startup, as shown in the following top-level example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://git/common/config-repo.git
          repos:
            team-a:
                pattern: team-a-*
                cloneOnStart: true
                uri: https://git/team-a/config-repo.git
            team-b:
                pattern: team-b-*
                cloneOnStart: false
                uri: https://git/team-b/config-repo.git
            team-c:
                pattern: team-c-*
                uri: https://git/team-a/config-repo.git
```

In the preceding example, the server clones team-a’s config-repo on
startup, before it accepts any requests. All other repositories are not
cloned until configuration from the repository is requested.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

Setting a repository to be cloned when the Config Server starts up can
help to identify a misconfigured configuration source (such as an
invalid repository URI) quickly, while the Config Server is starting up.
With `cloneOnStart`{.literal} not enabled for a configuration source,
the Config Server may start successfully with a misconfigured or invalid
configuration source and not detect an error until an application
requests configuration from that configuration source.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_authentication)Authentication {.title}

To use HTTP basic authentication on the remote repository, add the
`username`{.literal} and `password`{.literal} properties separately (not
in the URL), as shown in the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          username: trolley
          password: strongpassword
```

If you do not use HTTPS and user credentials, SSH should also work out
of the box when you store keys in the default directories
(`~/.ssh`{.literal}) and the URI points to an SSH location, such as
`git@github.com:configuration/cloud-configuration`{.literal}. It is
important that an entry for the Git server be present in the
`~/.ssh/known_hosts`{.literal} file and that it is in
`ssh-rsa`{.literal} format. Other formats (such as
`ecdsa-sha2-nistp256`{.literal}) are not supported. To avoid surprises,
you should ensure that only one entry is present in the
`known_hosts`{.literal} file for the Git server and that it matches the
URL you provided to the config server. If you use a hostname in the URL,
you want to have exactly that (not the IP) in the
`known_hosts`{.literal} file. The repository is accessed by using JGit,
so any documentation you find on that should be applicable. HTTPS proxy
settings can be set in `~/.git/config`{.literal} or (in the same way as
for any other JVM process) with system properties
(`-Dhttps.proxyHost`{.literal} and `-Dhttps.proxyPort`{.literal}).

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

If you do not know where your `~/.git`{.literal} directory is, use
`git config --global`{.literal} to manipulate the settings (for example,
`git config --global http.sslVerify false`{.literal}).

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_authentication_with_aws_codecommit)Authentication with AWS CodeCommit {.title}

Spring Cloud Config Server also supports [AWS
CodeCommit](https://docs.aws.amazon.com/codecommit/latest/userguide/welcome.html)
authentication. AWS CodeCommit uses an authentication helper when using
Git from the command line. This helper is not used with the JGit
library, so a JGit CredentialProvider for AWS CodeCommit is created if
the Git URI matches the AWS CodeCommit pattern. AWS CodeCommit URIs
follow this
pattern://git-codecommit.\${AWS\_REGION}.amazonaws.com/\${repopath}.

If you provide a username and password with an AWS CodeCommit URI, they
must be the [AWS accessKeyId and
secretAccessKey](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSGettingStartedGuide/AWSCredentials.html)
that provide access to the repository. If you do not specify a username
and password, the accessKeyId and secretAccessKey are retrieved by using
the [AWS Default Credential Provider
Chain](https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/credentials.html).

If your Git URI matches the CodeCommit URI pattern (shown earlier), you
must provide valid AWS credentials in the username and password or in
one of the locations supported by the default credential provider chain.
AWS EC2 instances may use [IAM Roles for EC2
Instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/iam-roles-for-amazon-ec2.html).

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The `aws-java-sdk-core`{.literal} jar is an optional dependency. If the
`aws-java-sdk-core`{.literal} jar is not on your classpath, the AWS Code
Commit credential provider is not created, regardless of the git server
URI.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_git_ssh_configuration_using_properties)Git SSH configuration using properties {.title}

By default, the JGit library used by Spring Cloud Config Server uses SSH
configuration files such as `~/.ssh/known_hosts`{.literal} and
`/etc/ssh/ssh_config`{.literal} when connecting to Git repositories by
using an SSH URI. In cloud environments such as Cloud Foundry, the local
filesystem may be ephemeral or not easily accessible. For those cases,
SSH configuration can be set by using Java properties. In order to
activate property-based SSH configuration, the
`spring.cloud.config.server.git.ignoreLocalSshSettings`{.literal}
property must be set to `true`{.literal}, as shown in the following
example:

``` {.programlisting}
  spring:
    cloud:
      config:
        server:
          git:
            uri: git@gitserver.com:team/repo1.git
            ignoreLocalSshSettings: true
            hostKey: someHostKey
            hostKeyAlgorithm: ssh-rsa
            privateKey: |
                         -----BEGIN RSA PRIVATE KEY-----
                         MIIEpgIBAAKCAQEAx4UbaDzY5xjW6hc9jwN0mX33XpTDVW9WqHp5AKaRbtAC3DqX
                         IXFMPgw3K45jxRb93f8tv9vL3rD9CUG1Gv4FM+o7ds7FRES5RTjv2RT/JVNJCoqF
                         ol8+ngLqRZCyBtQN7zYByWMRirPGoDUqdPYrj2yq+ObBBNhg5N+hOwKjjpzdj2Ud
                         1l7R+wxIqmJo1IYyy16xS8WsjyQuyC0lL456qkd5BDZ0Ag8j2X9H9D5220Ln7s9i
                         oezTipXipS7p7Jekf3Ywx6abJwOmB0rX79dV4qiNcGgzATnG1PkXxqt76VhcGa0W
                         DDVHEEYGbSQ6hIGSh0I7BQun0aLRZojfE3gqHQIDAQABAoIBAQCZmGrk8BK6tXCd
                         fY6yTiKxFzwb38IQP0ojIUWNrq0+9Xt+NsypviLHkXfXXCKKU4zUHeIGVRq5MN9b
                         BO56/RrcQHHOoJdUWuOV2qMqJvPUtC0CpGkD+valhfD75MxoXU7s3FK7yjxy3rsG
                         EmfA6tHV8/4a5umo5TqSd2YTm5B19AhRqiuUVI1wTB41DjULUGiMYrnYrhzQlVvj
                         5MjnKTlYu3V8PoYDfv1GmxPPh6vlpafXEeEYN8VB97e5x3DGHjZ5UrurAmTLTdO8
                         +AahyoKsIY612TkkQthJlt7FJAwnCGMgY6podzzvzICLFmmTXYiZ/28I4BX/mOSe
                         pZVnfRixAoGBAO6Uiwt40/PKs53mCEWngslSCsh9oGAaLTf/XdvMns5VmuyyAyKG
                         ti8Ol5wqBMi4GIUzjbgUvSUt+IowIrG3f5tN85wpjQ1UGVcpTnl5Qo9xaS1PFScQ
                         xrtWZ9eNj2TsIAMp/svJsyGG3OibxfnuAIpSXNQiJPwRlW3irzpGgVx/AoGBANYW
                         dnhshUcEHMJi3aXwR12OTDnaLoanVGLwLnkqLSYUZA7ZegpKq90UAuBdcEfgdpyi
                         PhKpeaeIiAaNnFo8m9aoTKr+7I6/uMTlwrVnfrsVTZv3orxjwQV20YIBCVRKD1uX
                         VhE0ozPZxwwKSPAFocpyWpGHGreGF1AIYBE9UBtjAoGBAI8bfPgJpyFyMiGBjO6z
                         FwlJc/xlFqDusrcHL7abW5qq0L4v3R+FrJw3ZYufzLTVcKfdj6GelwJJO+8wBm+R
                         gTKYJItEhT48duLIfTDyIpHGVm9+I1MGhh5zKuCqIhxIYr9jHloBB7kRm0rPvYY4
                         VAykcNgyDvtAVODP+4m6JvhjAoGBALbtTqErKN47V0+JJpapLnF0KxGrqeGIjIRV
                         cYA6V4WYGr7NeIfesecfOC356PyhgPfpcVyEztwlvwTKb3RzIT1TZN8fH4YBr6Ee
                         KTbTjefRFhVUjQqnucAvfGi29f+9oE3Ei9f7wA+H35ocF6JvTYUsHNMIO/3gZ38N
                         CPjyCMa9AoGBAMhsITNe3QcbsXAbdUR00dDsIFVROzyFJ2m40i4KCRM35bC/BIBs
                         q0TY3we+ERB40U8Z2BvU61QuwaunJ2+uGadHo58VSVdggqAo0BSkH58innKKt96J
                         69pcVH/4rmLbXdcmNYGm6iu+MlPQk4BUZknHSmVHIFdJ0EPupVaQ8RHT
                         -----END RSA PRIVATE KEY-----
```

The following table describes the SSH configuration properties.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#d0e633)

**Table 2.1. SSH Configuration Properties**

  Property Name                  Remarks
  ------------------------------ --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **ignoreLocalSshSettings**     If `true`{.literal}, use property-based instead of file-based SSH config. Must be set at as `spring.cloud.config.server.git.ignoreLocalSshSettings`{.literal}, **not** inside a repository definition.
  **privateKey**                 Valid SSH private key. Must be set if `ignoreLocalSshSettings`{.literal} is true and Git URI is SSH format.
  **hostKey**                    Valid SSH host key. Must be set if `hostKeyAlgorithm`{.literal} is also set.
  **hostKeyAlgorithm**           One of `ssh-dss, ssh-rsa, ecdsa-sha2-nistp256, ecdsa-sha2-nistp384, or ecdsa-sha2-nistp521`{.literal}. Must be set if `hostKey`{.literal} is also set.
  **strictHostKeyChecking**      `true`{.literal} or `false`{.literal}. If false, ignore errors with host key.
  **knownHostsFile**             Location of custom `.known_hosts`{.literal} file.
  **preferredAuthentications**   Override server authentication method order. This should allow for evading login prompts if server has keyboard-interactive authentication before the `publickey`{.literal} method.

\

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_placeholders_in_git_search_paths)Placeholders in Git Search Paths {.title}

Spring Cloud Config Server also supports a search path with placeholders
for the `{application}`{.literal} and `{profile}`{.literal} (and
`{label}`{.literal} if you need it), as shown in the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          searchPaths: '{application}'
```

The preceding listing causes a search of the repository for files in the
same name as the directory (as well as the top level). Wildcards are
also valid in a search path with placeholders (any matching directory is
included in the search).

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_force_pull_in_git_repositories)Force pull in Git Repositories {.title}

As mentioned earlier, Spring Cloud Config Server makes a clone of the
remote git repository in case the local copy gets dirty (for example,
folder content changes by an OS process) such that Spring Cloud Config
Server cannot update the local copy from remote repository.

To solve this issue, there is a `force-pull`{.literal} property that
makes Spring Cloud Config Server force pull from the remote repository
if the local copy is dirty, as shown in the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          force-pull: true
```

If you have a multiple-repositories configuration, you can configure the
`force-pull`{.literal} property per repository, as shown in the
following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://git/common/config-repo.git
          force-pull: true
          repos:
            team-a:
                pattern: team-a-*
                uri: https://git/team-a/config-repo.git
                force-pull: true
            team-b:
                pattern: team-b-*
                uri: https://git/team-b/config-repo.git
                force-pull: true
            team-c:
                pattern: team-c-*
                uri: https://git/team-a/config-repo.git
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The default value for `force-pull`{.literal} property is
`false`{.literal}.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_deleting_untracked_branches_in_git_repositories)Deleting untracked branches in Git Repositories {.title}

As Spring Cloud Config Server has a clone of the remote git repository
after check-outing branch to local repo (e.g fetching properties by
label) it will keep this branch forever or till the next server restart
(which creates new local repo). So there could be a case when remote
branch is deleted but local copy of it is still available for fetching.
And if Spring Cloud Config Server client service starts with
`--spring.cloud.config.label=deletedRemoteBranch,master`{.literal} it
will fetch properties from `deletedRemoteBranch`{.literal} local branch,
but not from `master`{.literal}.

In order to keep local repository branches clean and up to remote -
`deleteUntrackedBranches`{.literal} property could be set. It will make
Spring Cloud Config Server **force** delete untracked branches from
local repository. Example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          deleteUntrackedBranches: true
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The default value for `deleteUntrackedBranches`{.literal} property is
`false`{.literal}.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_git_refresh_rate)Git Refresh Rate {.title}

You can control how often the config server will fetch updated
configuration data from your Git backend by using
`spring.cloud.config.server.git.refreshRate`{.literal}. The value of
this property is specified in seconds. By default the value is 0,
meaning the config server will fetch updated configuration from the Git
repo every time it is requested.

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_version_control_backend_filesystem_use)2.1.2 Version Control Backend Filesystem Use {.title}

![[Warning]](./Spring%20Cloud%20Config_files/warning.png)

Warning

With VCS-based backends (git, svn), files are checked out or cloned to
the local filesystem. By default, they are put in the system temporary
directory with a prefix of `config-repo-`{.literal}. On linux, for
example, it could be `/tmp/config-repo-<randomid>`{.literal}. Some
operating systems [routinely clean
out](https://serverfault.com/questions/377348/when-does-tmp-get-cleared/377349#377349)
temporary directories. This can lead to unexpected behavior, such as
missing properties. To avoid this problem, change the directory that
Config Server uses by setting
`spring.cloud.config.server.git.basedir`{.literal} or
`spring.cloud.config.server.svn.basedir`{.literal} to a directory that
does not reside in the system temp structure.

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_file_system_backend)2.1.3 File System Backend {.title}

There is also a “native” profile in the Config Server that does not use
Git but loads the config files from the local classpath or file system
(any static URL you want to point to with
`spring.cloud.config.server.native.searchLocations`{.literal}). To use
the native profile, launch the Config Server with
`spring.profiles.active=native`{.literal}.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

Remember to use the `file:`{.literal} prefix for file resources (the
default without a prefix is usually the classpath). As with any Spring
Boot configuration, you can embed `${}`{.literal}-style environment
placeholders, but remember that absolute paths in Windows require an
extra `/`{.literal} (for example,
`file:///${user.home}/config-repo`{.literal}).

![[Warning]](./Spring%20Cloud%20Config_files/warning.png)

Warning

The default value of the `searchLocations`{.literal} is identical to a
local Spring Boot application (that is,
`[classpath:/, classpath:/config, file:./, file:./config]`{.literal}).
This does not expose the `application.properties`{.literal} from the
server to all clients, because any property sources present in the
server are removed before being sent to the client.

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

A filesystem backend is great for getting started quickly and for
testing. To use it in production, you need to be sure that the file
system is reliable and shared across all instances of the Config Server.

The search locations can contain placeholders for
`{application}`{.literal}, `{profile}`{.literal}, and
`{label}`{.literal}. In this way, you can segregate the directories in
the path and choose a strategy that makes sense for you (such as
subdirectory per application or subdirectory per profile).

If you do not use placeholders in the search locations, this repository
also appends the `{label}`{.literal} parameter of the HTTP resource to a
suffix on the search path, so properties files are loaded from each
search location **and** a subdirectory with the same name as the label
(the labelled properties take precedence in the Spring Environment).
Thus, the default behaviour with no placeholders is the same as adding a
search location ending with `/{label}/`{.literal}. For example,
`file:/tmp/config`{.literal} is the same as
`file:/tmp/config,file:/tmp/config/{label}`{.literal}. This behavior can
be disabled by setting
`spring.cloud.config.server.native.addLabelLocations=false`{.literal}.

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#vault-backend)2.1.4 Vault Backend {.title}

Spring Cloud Config Server also supports
[Vault](https://www.vaultproject.io/) as a backend.

****

Vault is a tool for securely accessing secrets. A secret is anything
that to which you want to tightly control access, such as API keys,
passwords, certificates, and other sensitive information. Vault provides
a unified interface to any secret while providing tight access control
and recording a detailed audit log.

For more information on Vault, see the [Vault quick start
guide](https://learn.hashicorp.com/vault/?track=getting-started#getting-started).

To enable the config server to use a Vault backend, you can run your
config server with the `vault`{.literal} profile. For example, in your
config server’s `application.properties`{.literal}, you can add
`spring.profiles.active=vault`{.literal}.

By default, the config server assumes that your Vault server runs at
`http://127.0.0.1:8200`{.literal}. It also assumes that the name of
backend is `secret`{.literal} and the key is `application`{.literal}.
All of these defaults can be configured in your config server’s
`application.properties`{.literal}. The following table describes
configurable Vault properties:

  Name                Default Value
  ------------------- ---------------
  host                127.0.0.1
  port                8200
  scheme              http
  backend             secret
  defaultKey          application
  profileSeparator    ,
  kvVersion           1
  skipSslValidation   false
  timeout             5
  namespace           null

![[Important]](./Spring%20Cloud%20Config_files/important.png)

Important

All of the properties in the preceding table must be prefixed with
`spring.cloud.config.server.vault`{.literal} or placed in the correct
Vault section of a composite configuration.

All configurable properties can be found in
`org.springframework.cloud.config.server.environment.VaultEnvironmentProperties`{.literal}.

Vault 0.10.0 introduced a versioned key-value backend (k/v backend
version 2) that exposes a different API than earlier versions, it now
requires a `data/`{.literal} between the mount path and the actual
context path and wraps secrets in a `data`{.literal} object. Setting
`kvVersion=2`{.literal} will take this into account.

Optionally, there is support for the Vault Enterprise
`X-Vault-Namespace`{.literal} header. To have it sent to Vault set the
`namespace`{.literal} property.

With your config server running, you can make HTTP requests to the
server to retrieve values from the Vault backend. To do so, you need a
token for your Vault server.

First, place some data in you Vault, as shown in the following example:

``` {.programlisting}
$ vault kv put secret/application foo=bar baz=bam
$ vault kv put secret/myapp foo=myappsbar
```

Second, make an HTTP request to your config server to retrieve the
values, as shown in the following example:

`$ curl -X "GET" "http://localhost:8888/myapp/default" -H "X-Config-Token: yourtoken"`{.literal}

You should see a response similar to the following:

``` {.programlisting}
{
   "name":"myapp",
   "profiles":[
      "default"
   ],
   "label":null,
   "version":null,
   "state":null,
   "propertySources":[
      {
         "name":"vault:myapp",
         "source":{
            "foo":"myappsbar"
         }
      },
      {
         "name":"vault:application",
         "source":{
            "baz":"bam",
            "foo":"bar"
         }
      }
   ]
}
```

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_multiple_properties_sources)Multiple Properties Sources {.title}

When using Vault, you can provide your applications with multiple
properties sources. For example, assume you have written data to the
following paths in Vault:

``` {.programlisting}
secret/myApp,dev
secret/myApp
secret/application,dev
secret/application
```

Properties written to `secret/application`{.literal} are available to
[all applications using the Config
Server](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#).
An application with the name, `myApp`{.literal}, would have any
properties written to `secret/myApp`{.literal} and
`secret/application`{.literal} available to it. When `myApp`{.literal}
has the `dev`{.literal} profile enabled, properties written to all of
the above paths would be available to it, with properties in the first
path in the list taking priority over the others.

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_accessing_backends_through_a_proxy)2.1.5 Accessing Backends Through a Proxy {.title}

The configuration server can access a Git or Vault backend through an
HTTP or HTTPS proxy. This behavior is controlled for either Git or Vault
by settings under `proxy.http`{.literal} and `proxy.https`{.literal}.
These settings are per repository, so if you are using a [composite
environment
repository](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#composite-environment-repositories "2.1.9 Composite Environment Repositories")
you must configure proxy settings for each backend in the composite
individually. If using a network which requires separate proxy servers
for HTTP and HTTPS URLs, you can configure both the HTTP and the HTTPS
proxy settings for a single backend.

The following table describes the proxy configuration properties for
both HTTP and HTTPS proxies. All of these properties must be prefixed by
`proxy.http`{.literal} or `proxy.https`{.literal}.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#d0e1138)

**Table 2.2. Proxy Configuration Properties**

  Property Name       Remarks
  ------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **host**            The host of the proxy.
  **port**            The port with which to access the proxy.
  **nonProxyHosts**   Any hosts which the configuration server should access outside the proxy. If values are provided for both `proxy.http.nonProxyHosts`{.literal} and `proxy.https.nonProxyHosts`{.literal}, the `proxy.http`{.literal} value will be used.
  **username**        The username with which to authenticate to the proxy. If values are provided for both `proxy.http.username`{.literal} and `proxy.https.username`{.literal}, the `proxy.http`{.literal} value will be used.
  **password**        The password with which to authenticate to the proxy. If values are provided for both `proxy.http.password`{.literal} and `proxy.https.password`{.literal}, the `proxy.http`{.literal} value will be used.

\

The following configuration uses an HTTPS proxy to access a Git
repository.

``` {.programlisting}
spring:
  profiles:
    active: git
  cloud:
    config:
      server:
        git:
          uri: https://github.com/spring-cloud-samples/config-repo
          proxy:
            https:
              host: my-proxy.host.io
              password: myproxypassword
              port: '3128'
              username: myproxyusername
              nonProxyHosts: example.com
```

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_sharing_configuration_with_all_applications)2.1.6 Sharing Configuration With All Applications {.title}

Sharing configuration between all applications varies according to which
approach you take, as described in the following topics:

-   [the section called “File Based
    Repositories”](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#spring-cloud-config-server-file-based-repositories "File Based Repositories")
-   [the section called “Vault
    Server”](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#spring-cloud-config-server-vault-server "Vault Server")

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#spring-cloud-config-server-file-based-repositories)File Based Repositories {.title}

With file-based (git, svn, and native) repositories, resources with file
names in `application*`{.literal} (`application.properties`{.literal},
`application.yml`{.literal}, `application-*.properties`{.literal}, and
so on) are shared between all client applications. You can use resources
with these file names to configure global defaults and have them be
overridden by application-specific files as necessary.

The \#\_property\_overrides[property overrides] feature can also be used
for setting global defaults, with placeholders applications allowed to
override them locally.

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

With the “native” profile (a local file system backend) , you should use
an explicit search location that is not part of the server’s own
configuration. Otherwise, the `application*`{.literal} resources in the
default search locations get removed because they are part of the
server.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#spring-cloud-config-server-vault-server)Vault Server {.title}

When using Vault as a backend, you can share configuration with all
applications by placing configuration in `secret/application`{.literal}.
For example, if you run the following Vault command, all applications
using the config server will have the properties `foo`{.literal} and
`baz`{.literal} available to them:

``` {.programlisting}
$ vault write secret/application foo=bar baz=bam
```

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_jdbc_backend)2.1.7 JDBC Backend {.title}

Spring Cloud Config Server supports JDBC (relational database) as a
backend for configuration properties. You can enable this feature by
adding `spring-jdbc`{.literal} to the classpath and using the
`jdbc`{.literal} profile or by adding a bean of type
`JdbcEnvironmentRepository`{.literal}. If you include the right
dependencies on the classpath (see the user guide for more details on
that), Spring Boot configures a data source.

The database needs to have a table called `PROPERTIES`{.literal} with
columns called `APPLICATION`{.literal}, `PROFILE`{.literal}, and
`LABEL`{.literal} (with the usual `Environment`{.literal} meaning), plus
`KEY`{.literal} and `VALUE`{.literal} for the key and value pairs in
`Properties`{.literal} style. All fields are of type String in Java, so
you can make them `VARCHAR`{.literal} of whatever length you need.
Property values behave in the same way as they would if they came from
Spring Boot properties files named
`{application}-{profile}.properties`{.literal}, including all the
encryption and decryption, which will be applied as post-processing
steps (that is, not in the repository implementation directly).

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_credhub_backend)2.1.8 CredHub Backend {.title}

Spring Cloud Config Server supports
[CredHub](https://docs.cloudfoundry.org/credhub) as a backend for
configuration properties. You can enable this feature by adding a
dependency to [Spring
CredHub](https://spring.io/projects/spring-credhub).

**pom.xml. **

``` {.programlisting}
<dependencies>
    <dependency>
        <groupId>org.springframework.credhub</groupId>
        <artifactId>spring-credhub-starter</artifactId>
    </dependency>
</dependencies>
```

The following configuration uses mutual TLS to access a CredHub:

``` {.programlisting}
spring:
  profiles:
    active: credhub
  cloud:
    config:
      server:
        credhub:
          url: https://credhub:8844
```

The properties should be stored as JSON, such as:

``` {.programlisting}
credhub set --name "/demo-app/default/master/toggles" --type=json
value: {"toggle.button": "blue", "toggle.link": "red"}
```

``` {.programlisting}
credhub set --name "/demo-app/default/master/abs" --type=json
value: {"marketing.enabled": true, "external.enabled": false}
```

All client applications with the name
`spring.cloud.config.name=demo-app`{.literal} will have the following
properties available to them:

``` {.screen}
{
    toggle.button: "blue",
    toggle.link: "red",
    marketing.enabled: true,
    external.enabled: false
}
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

When no profile is specified `default`{.literal} will be used and when
no label is specified `master`{.literal} will be used as a default
value.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_oauth_2_0)OAuth 2.0 {.title}

You can authenticate with [OAuth 2.0](https://oauth.net/2/) using
[UAA](https://docs.cloudfoundry.org/concepts/architecture/uaa.html) as a
provider.

**pom.xml. **

``` {.programlisting}
<dependencies>
    <dependency>
        <groupId>org.springframework.security</groupId>
        <artifactId>spring-security-config</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.security</groupId>
        <artifactId>spring-security-oauth2-client</artifactId>
    </dependency>
</dependencies>
```

The following configuration uses OAuth 2.0 and UAA to access a CredHub:

``` {.programlisting}
spring:
  profiles:
    active: credhub
  cloud:
    config:
      server:
        credhub:
          url: https://credhub:8844
          oauth2:
            registration-id: credhub-client
  security:
    oauth2:
      client:
        registration:
          credhub-client:
            provider: uaa
            client-id: credhub_config_server
            client-secret: asecret
            authorization-grant-type: client_credentials
        provider:
          uaa:
            token-uri: https://uaa:8443/oauth/token
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The used UAA client-id should have `credhub.read`{.literal} as scope.

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#composite-environment-repositories)2.1.9 Composite Environment Repositories {.title}

In some scenarios, you may wish to pull configuration data from multiple
environment repositories. To do so, you can enable the
`composite`{.literal} profile in your configuration server’s application
properties or YAML file. If, for example, you want to pull configuration
data from a Subversion repository as well as two Git repositories, you
can set the following properties for your configuration server:

``` {.programlisting}
spring:
  profiles:
    active: composite
  cloud:
    config:
      server:
        composite:
        -
          type: svn
          uri: file:///path/to/svn/repo
        -
          type: git
          uri: file:///path/to/rex/git/repo
        -
          type: git
          uri: file:///path/to/walter/git/repo
```

Using this configuration, precedence is determined by the order in which
repositories are listed under the `composite`{.literal} key. In the
above example, the Subversion repository is listed first, so a value
found in the Subversion repository will override values found for the
same property in one of the Git repositories. A value found in the
`rex`{.literal} Git repository will be used before a value found for the
same property in the `walter`{.literal} Git repository.

If you want to pull configuration data only from repositories that are
each of distinct types, you can enable the corresponding profiles,
rather than the `composite`{.literal} profile, in your configuration
server’s application properties or YAML file. If, for example, you want
to pull configuration data from a single Git repository and a single
HashiCorp Vault server, you can set the following properties for your
configuration server:

``` {.programlisting}
spring:
  profiles:
    active: git, vault
  cloud:
    config:
      server:
        git:
          uri: file:///path/to/git/repo
          order: 2
        vault:
          host: 127.0.0.1
          port: 8200
          order: 1
```

Using this configuration, precedence can be determined by an
`order`{.literal} property. You can use the `order`{.literal} property
to specify the priority order for all your repositories. The lower the
numerical value of the `order`{.literal} property, the higher priority
it has. The priority order of a repository helps resolve any potential
conflicts between repositories that contain values for the same
properties.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

If your composite environment includes a Vault server as in the previous
example, you must include a Vault token in every request made to the
configuration server. See [Vault
Backend](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#vault-backend "2.1.4 Vault Backend").

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

Any type of failure when retrieving values from an environment
repository results in a failure for the entire composite environment.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

When using a composite environment, it is important that all
repositories contain the same labels. If you have an environment similar
to those in the preceding examples and you request configuration data
with the `master`{.literal} label but the Subversion repository does not
contain a branch called `master`{.literal}, the entire request fails.

#### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_custom_composite_environment_repositories)Custom Composite Environment Repositories {.title}

In addition to using one of the environment repositories from Spring
Cloud, you can also provide your own `EnvironmentRepository`{.literal}
bean to be included as part of a composite environment. To do so, your
bean must implement the `EnvironmentRepository`{.literal} interface. If
you want to control the priority of your custom
`EnvironmentRepository`{.literal} within the composite environment, you
should also implement the `Ordered`{.literal} interface and override the
`getOrdered`{.literal} method. If you do not implement the
`Ordered`{.literal} interface, your `EnvironmentRepository`{.literal} is
given the lowest priority.

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_property_overrides)2.1.10 Property Overrides {.title}

The Config Server has an “overrides” feature that lets the operator
provide configuration properties to all applications. The overridden
properties cannot be accidentally changed by the application with the
normal Spring Boot hooks. To declare overrides, add a map of name-value
pairs to `spring.cloud.config.server.overrides`{.literal}, as shown in
the following example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        overrides:
          foo: bar
```

The preceding examples causes all applications that are config clients
to read `foo=bar`{.literal}, independent of their own configuration.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

A configuration system cannot force an application to use configuration
data in any particular way. Consequently, overrides are not enforceable.
However, they do provide useful default behavior for Spring Cloud Config
clients.

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

Normally, Spring environment placeholders with `${}`{.literal} can be
escaped (and resolved on the client) by using backslash (`\`{.literal})
to escape the `$`{.literal} or the `{`{.literal}. For example,
`\${app.foo:bar}`{.literal} resolves to `bar`{.literal}, unless the app
provides its own `app.foo`{.literal}.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

In YAML, you do not need to escape the backslash itself. However, in
properties files, you do need to escape the backslash, when you
configure the overrides on the server.

You can change the priority of all overrides in the client to be more
like default values, letting applications supply their own values in
environment variables or System properties, by setting the
`spring.cloud.config.overrideNone=true`{.literal} flag (the default is
false) in the remote repository.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_health_indicator)2.2 Health Indicator {.title style="clear: both"}
-------------------------------------------------------------------------------------------------------------------------------------------------------

Config Server comes with a Health Indicator that checks whether the
configured `EnvironmentRepository`{.literal} is working. By default, it
asks the `EnvironmentRepository`{.literal} for an application named
`app`{.literal}, the `default`{.literal} profile, and the default label
provided by the `EnvironmentRepository`{.literal} implementation.

You can configure the Health Indicator to check more applications along
with custom profiles and custom labels, as shown in the following
example:

``` {.programlisting}
spring:
  cloud:
    config:
      server:
        health:
          repositories:
            myservice:
              label: mylabel
            myservice-dev:
              name: myservice
              profiles: development
```

You can disable the Health Indicator by setting
`spring.cloud.config.server.health.enabled=false`{.literal}.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_security)2.3 Security {.title style="clear: both"}
---------------------------------------------------------------------------------------------------------------------------------------

You can secure your Config Server in any way that makes sense to you
(from physical network security to OAuth2 bearer tokens), because Spring
Security and Spring Boot offer support for many security arrangements.

To use the default Spring Boot-configured HTTP Basic security, include
Spring Security on the classpath (for example, through
`spring-boot-starter-security`{.literal}). The default is a username of
`user`{.literal} and a randomly generated password. A random password is
not useful in practice, so we recommend you configure the password (by
setting `spring.security.user.password`{.literal}) and encrypt it (see
below for instructions on how to do that).

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_encryption_and_decryption)2.4 Encryption and Decryption {.title style="clear: both"}
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![[Important]](./Spring%20Cloud%20Config_files/important.png)

Important

To use the encryption and decryption features you need the full-strength
JCE installed in your JVM (it is not included by default). You can
download the “Java Cryptography Extension (JCE) Unlimited Strength
Jurisdiction Policy Files” from Oracle and follow the installation
instructions (essentially, you need to replace the two policy files in
the JRE lib/security directory with the ones that you downloaded).

If the remote property sources contain encrypted content (values
starting with `{cipher}`{.literal}), they are decrypted before sending
to clients over HTTP. The main advantage of this setup is that the
property values need not be in plain text when they are “at rest” (for
example, in a git repository). If a value cannot be decrypted, it is
removed from the property source and an additional property is added
with the same key but prefixed with `invalid`{.literal} and a value that
means “not applicable” (usually `<n/a>`{.literal}). This is largely to
prevent cipher text being used as a password and accidentally leaking.

If you set up a remote config repository for config client applications,
it might contain an `application.yml`{.literal} similar to the
following:

**application.yml. **

``` {.programlisting}
spring:
  datasource:
    username: dbuser
    password: '{cipher}FKSAJDFGYOS8F7GLHAKERGFHLSAJ'
```

Encrypted values in a .properties file must not be wrapped in quotes.
Otherwise, the value is not decrypted. The following example shows
values that would work:

**application.properties. **

``` {.screen}
spring.datasource.username: dbuser
spring.datasource.password: {cipher}FKSAJDFGYOS8F7GLHAKERGFHLSAJ
```

You can safely push this plain text to a shared git repository, and the
secret password remains protected.

The server also exposes `/encrypt`{.literal} and `/decrypt`{.literal}
endpoints (on the assumption that these are secured and only accessed by
authorized agents). If you edit a remote config file, you can use the
Config Server to encrypt values by POSTing to the `/encrypt`{.literal}
endpoint, as shown in the following example:

``` {.screen}
$ curl localhost:8888/encrypt -d mysecret
682bc583f4641835fa2db009355293665d2647dade3375c0ee201de2a49f7bda
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

If the value you encrypt has characters in it that need to be URL
encoded, you should use the `--data-urlencode`{.literal} option to
`curl`{.literal} to make sure they are encoded properly.

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

Be sure not to include any of the curl command statistics in the
encrypted value. Outputting the value to a file can help avoid this
problem.

The inverse operation is also available through `/decrypt`{.literal}
(provided the server is configured with a symmetric key or a full key
pair), as shown in the following example:

``` {.screen}
$ curl localhost:8888/decrypt -d 682bc583f4641835fa2db009355293665d2647dade3375c0ee201de2a49f7bda
mysecret
```

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

If you testing with curl, then use `--data-urlencode`{.literal} (instead
of `-d`{.literal}) or set an explicit
`Content-Type: text/plain`{.literal} to make sure curl encodes the data
correctly when there are special characters ('+' is particularly
tricky).

Take the encrypted value and add the `{cipher}`{.literal} prefix before
you put it in the YAML or properties file and before you commit and push
it to a remote (potentially insecure) store.

The `/encrypt`{.literal} and `/decrypt`{.literal} endpoints also both
accept paths in the form of `/*/{name}/{profiles}`{.literal}, which can
be used to control cryptography on a per-application (name) and
per-profile basis when clients call into the main environment resource.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

To control the cryptography in this granular way, you must also provide
a `@Bean`{.literal} of type `TextEncryptorLocator`{.literal} that
creates a different encryptor per name and profiles. The one that is
provided by default does not do so (all encryptions use the same key).

The `spring`{.literal} command line client (with Spring Cloud CLI
extensions installed) can also be used to encrypt and decrypt, as shown
in the following example:

``` {.screen}
$ spring encrypt mysecret --key foo
682bc583f4641835fa2db009355293665d2647dade3375c0ee201de2a49f7bda
$ spring decrypt --key foo 682bc583f4641835fa2db009355293665d2647dade3375c0ee201de2a49f7bda
mysecret
```

To use a key in a file (such as an RSA public key for encryption),
prepend the key value with "@" and provide the file path, as shown in
the following example:

``` {.screen}
$ spring encrypt mysecret --key @${HOME}/.ssh/id_rsa.pub
AQAjPgt3eFZQXwt8tsHAVv/QHiY5sI2dRcR+...
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The `--key`{.literal} argument is mandatory (despite having a
`--`{.literal} prefix).

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_key_management)2.5 Key Management {.title style="clear: both"}
---------------------------------------------------------------------------------------------------------------------------------------------------

The Config Server can use a symmetric (shared) key or an asymmetric one
(RSA key pair). The asymmetric choice is superior in terms of security,
but it is often more convenient to use a symmetric key since it is a
single property value to configure in the
`bootstrap.properties`{.literal}.

To configure a symmetric key, you need to set `encrypt.key`{.literal} to
a secret String (or use the `ENCRYPT_KEY`{.literal} environment variable
to keep it out of plain-text configuration files).

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

You cannot configure an asymmetric key using `encrypt.key`{.literal}.

To configure an asymmetric key use a keystore (e.g. as created by the
`keytool`{.literal} utility that comes with the JDK). The keystore
properties are `encrypt.keyStore.*`{.literal} with `*`{.literal} equal
to

  Property                                Description
  --------------------------------------- --------------------------------------------------------------
  `encrypt.keyStore.location`{.literal}   Contains a `Resource`{.literal} location
  `encrypt.keyStore.password`{.literal}   Holds the password that unlocks the keystore
  `encrypt.keyStore.alias`{.literal}      Identifies which key in the store to use
  `encrypt.keyStore.type`{.literal}       The type of KeyStore to create. Defaults to `jks`{.literal}.

The encryption is done with the public key, and a private key is needed
for decryption. Thus, in principle, you can configure only the public
key in the server if you want to only encrypt (and are prepared to
decrypt the values yourself locally with the private key). In practice,
you might not want to do decrypt locally, because it spreads the key
management process around all the clients, instead of concentrating it
in the server. On the other hand, it can be a useful option if your
config server is relatively insecure and only a handful of clients need
the encrypted properties.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_creating_a_key_store_for_testing)2.6 Creating a Key Store for Testing {.title style="clear: both"}
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

To create a keystore for testing, you can use a command resembling the
following:

``` {.screen}
$ keytool -genkeypair -alias mytestkey -keyalg RSA \
  -dname "CN=Web Server,OU=Unit,O=Organization,L=City,S=State,C=US" \
  -keypass changeme -keystore server.jks -storepass letmein
```

Put the `server.jks`{.literal} file in the classpath (for instance) and
then, in your `bootstrap.yml`{.literal}, for the Config Server, create
the following settings:

``` {.programlisting}
encrypt:
  keyStore:
    location: classpath:/server.jks
    password: letmein
    alias: mytestkey
    secret: changeme
```

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_using_multiple_keys_and_key_rotation)2.7 Using Multiple Keys and Key Rotation {.title style="clear: both"}
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

In addition to the `{cipher}`{.literal} prefix in encrypted property
values, the Config Server looks for zero or more
`{name:value}`{.literal} prefixes before the start of the (Base64
encoded) cipher text. The keys are passed to a
`TextEncryptorLocator`{.literal}, which can do whatever logic it needs
to locate a `TextEncryptor`{.literal} for the cipher. If you have
configured a keystore (`encrypt.keystore.location`{.literal}), the
default locator looks for keys with aliases supplied by the
`key`{.literal} prefix, with a cipher text like resembling the
following:

``` {.programlisting}
foo:
  bar: `{cipher}{key:testkey}...`
```

The locator looks for a key named "testkey". A secret can also be
supplied by using a `{secret:…​}`{.literal} value in the prefix.
However, if it is not supplied, the default is to use the keystore
password (which is what you get when you build a keystore and do not
specify a secret). If you do supply a secret, you should also encrypt
the secret using a custom `SecretLocator`{.literal}.

When the keys are being used only to encrypt a few bytes of
configuration data (that is, they are not being used elsewhere), key
rotation is hardly ever necessary on cryptographic grounds. However, you
might occasionally need to change the keys (for example, in the event of
a security breach). In that case, all the clients would need to change
their source config files (for example, in git) and use a new
`{key:…​}`{.literal} prefix in all the ciphers. Note that the clients
need to first check that the key alias is available in the Config Server
keystore.

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

If you want to let the Config Server handle all encryption as well as
decryption, the `{name:value}`{.literal} prefixes can also be added as
plain text posted to the `/encrypt`{.literal} endpoint, .

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_serving_encrypted_properties)2.8 Serving Encrypted Properties {.title style="clear: both"}
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Sometimes you want the clients to decrypt the configuration locally,
instead of doing it in the server. In that case, if you provide the
`encrypt.*`{.literal} configuration to locate a key, you can still have
`/encrypt`{.literal} and `/decrypt`{.literal} endpoints, but you need to
explicitly switch off the decryption of outgoing properties by placing
`spring.cloud.config.server.encrypt.enabled=false`{.literal} in
`bootstrap.[yml|properties]`{.literal}. If you do not care about the
endpoints, it should work if you do not configure either the key or the
enabled flag.

The default JSON format from the environment endpoints is perfect for
consumption by Spring applications, because it maps directly onto the
`Environment`{.literal} abstraction. If you prefer, you can consume the
same data as YAML or Java properties by adding a suffix (".yml", ".yaml"
or ".properties") to the resource path. This can be useful for
consumption by applications that do not care about the structure of the
JSON endpoints or the extra metadata they provide (for example, an
application that is not using Spring might benefit from the simplicity
of this approach).

The YAML and properties representations have an additional flag
(provided as a boolean query parameter called
`resolvePlaceholders`{.literal}) to signal that placeholders in the
source documents (in the standard Spring `${…​}`{.literal} form) should
be resolved in the output before rendering, where possible. This is a
useful feature for consumers that do not know about the Spring
placeholder conventions.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

There are limitations in using the YAML or properties formats, mainly in
relation to the loss of metadata. For example, the JSON is structured as
an ordered list of property sources, with names that correlate with the
source. The YAML and properties forms are coalesced into a single map,
even if the origin of the values has multiple sources, and the names of
the original source files are lost. Also, the YAML representation is not
necessarily a faithful representation of the YAML source in a backing
repository either. It is constructed from a list of flat property
sources, and assumptions have to be made about the form of the keys.

Instead of using the `Environment`{.literal} abstraction (or one of the
alternative representations of it in YAML or properties format), your
applications might need generic plain-text configuration files that are
tailored to their environment. The Config Server provides these through
an additional endpoint at `/{name}/{profile}/{label}/{path}`{.literal},
where `name`{.literal}, `profile`{.literal}, and `label`{.literal} have
the same meaning as the regular environment endpoint, but
`path`{.literal} is a file name (such as `log.xml`{.literal}). The
source files for this endpoint are located in the same way as for the
environment endpoints. The same search path is used for properties and
YAML files. However, instead of aggregating all matching resources, only
the first one to match is returned.

After a resource is located, placeholders in the normal format
(`${…​}`{.literal}) are resolved by using the effective
`Environment`{.literal} for the supplied application name, profile, and
label. In this way, the resource endpoint is tightly integrated with the
environment endpoints. Consider the following example for a GIT or SVN
repository:

``` {.screen}
application.yml
nginx.conf
```

where `nginx.conf`{.literal} looks like this:

``` {.screen}
server {
    listen              80;
    server_name         ${nginx.server.name};
}
```

and `application.yml`{.literal} like this:

``` {.programlisting}
nginx:
  server:
    name: example.com
---
spring:
  profiles: development
nginx:
  server:
    name: develop.com
```

The `/foo/default/master/nginx.conf`{.literal} resource might be as
follows:

``` {.screen}
server {
    listen              80;
    server_name         example.com;
}
```

and `/foo/development/master/nginx.conf`{.literal} like this:

``` {.screen}
server {
    listen              80;
    server_name         develop.com;
}
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

As with the source files for environment configuration, the
`profile`{.literal} is used to resolve the file name. So, if you want a
profile-specific file, `/*/development/*/logback.xml`{.literal} can be
resolved by a file called `logback-development.xml`{.literal} (in
preference to `logback.xml`{.literal}).

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

If you do not want to supply the `label`{.literal} and let the server
use the default label, you can supply a `useDefaultLabel`{.literal}
request parameter. So, the preceding example for the `default`{.literal}
profile could be `/foo/default/nginx.conf?useDefaultLabel`{.literal}.

The Config Server runs best as a standalone application. However, if
need be, you can embed it in another application. To do so, use the
`@EnableConfigServer`{.literal} annotation. An optional property named
`spring.cloud.config.server.bootstrap`{.literal} can be useful in this
case. It is a flag to indicate whether the server should configure
itself from its own remote repository. By default, the flag is off,
because it can delay startup. However, when embedded in another
application, it makes sense to initialize the same way as any other
application. When setting
`spring.cloud.config.server.bootstrap`{.literal} to `true`{.literal} you
must also use a [composite environment repository
configuration](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#composite-environment-repositories "2.1.9 Composite Environment Repositories").
For example

``` {.programlisting}
spring:
  application:
    name: configserver
  profiles:
    active: composite
  cloud:
    config:
      server:
        composite:
          - type: native
            search-locations: ${HOME}/Desktop/config
        bootstrap: true
```

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

If you use the bootstrap flag, the config server needs to have its name
and repository URI configured in `bootstrap.yml`{.literal}.

To change the location of the server endpoints, you can (optionally) set
`spring.cloud.config.server.prefix`{.literal} (for example,
`/config`{.literal}), to serve the resources under a prefix. The prefix
should start but not end with a `/`{.literal}. It is applied to the
`@RequestMappings`{.literal} in the Config Server (that is, underneath
the Spring Boot `server.servletPath`{.literal} and
`server.contextPath`{.literal} prefixes).

If you want to read the configuration for an application directly from
the backend repository (instead of from the config server), you
basically want an embedded config server with no endpoints. You can
switch off the endpoints entirely by not using the
`@EnableConfigServer`{.literal} annotation (set
`spring.cloud.config.server.bootstrap=true`{.literal}).

Many source code repository providers (such as Github, Gitlab, Gitea,
Gitee, Gogs, or Bitbucket) notify you of changes in a repository through
a webhook. You can configure the webhook through the provider’s user
interface as a URL and a set of events in which you are interested. For
instance,
[Github](https://developer.github.com/v3/activity/events/types/#pushevent)
uses a POST to the webhook with a JSON body containing a list of commits
and a header (`X-Github-Event`{.literal}) set to `push`{.literal}. If
you add a dependency on the `spring-cloud-config-monitor`{.literal}
library and activate the Spring Cloud Bus in your Config Server, then a
`/monitor`{.literal} endpoint is enabled.

When the webhook is activated, the Config Server sends a
`RefreshRemoteApplicationEvent`{.literal} targeted at the applications
it thinks might have changed. The change detection can be strategized.
However, by default, it looks for changes in files that match the
application name (for example, `foo.properties`{.literal} is targeted at
the `foo`{.literal} application, while
`application.properties`{.literal} is targeted at all applications). The
strategy to use when you want to override the behavior is
`PropertyPathNotificationExtractor`{.literal}, which accepts the request
headers and body as parameters and returns a list of file paths that
changed.

The default configuration works out of the box with Github, Gitlab,
Gitea, Gitee, Gogs or Bitbucket. In addition to the JSON notifications
from Github, Gitlab, Gitee, or Bitbucket, you can trigger a change
notification by POSTing to `/monitor`{.literal} with form-encoded body
parameters in the pattern of `path={name}`{.literal}. Doing so
broadcasts to applications matching the `{name}`{.literal} pattern
(which can contain wildcards).

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The `RefreshRemoteApplicationEvent`{.literal} is transmitted only if the
`spring-cloud-bus`{.literal} is activated in both the Config Server and
in the client application.

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

The default configuration also detects filesystem changes in local git
repositories. In that case, the webhook is not used. However, as soon as
you edit a config file, a refresh is broadcast.

A Spring Boot application can take immediate advantage of the Spring
Config Server (or other external property sources provided by the
application developer). It also picks up some additional useful features
related to `Environment`{.literal} change events.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#config-first-bootstrap)7.1 Config First Bootstrap {.title style="clear: both"}
------------------------------------------------------------------------------------------------------------------------------------------------------------------

The default behavior for any application that has the Spring Cloud
Config Client on the classpath is as follows: When a config client
starts, it binds to the Config Server (through the
`spring.cloud.config.uri`{.literal} bootstrap configuration property)
and initializes Spring `Environment`{.literal} with remote property
sources.

The net result of this behavior is that all client applications that
want to consume the Config Server need a `bootstrap.yml`{.literal} (or
an environment variable) with the server address set in
`spring.cloud.config.uri`{.literal} (it defaults to
"http://localhost:8888").

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#discovery-first-bootstrap)7.2 Discovery First Bootstrap {.title style="clear: both"}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If you use a `DiscoveryClient`{.literal} implementation, such as Spring
Cloud Netflix and Eureka Service Discovery or Spring Cloud Consul, you
can have the Config Server register with the Discovery Service. However,
in the default “Config First” mode, clients cannot take advantage of the
registration.

If you prefer to use `DiscoveryClient`{.literal} to locate the Config
Server, you can do so by setting
`spring.cloud.config.discovery.enabled=true`{.literal} (the default is
`false`{.literal}). The net result of doing so is that client
applications all need a `bootstrap.yml`{.literal} (or an environment
variable) with the appropriate discovery configuration. For example,
with Spring Cloud Netflix, you need to define the Eureka server address
(for example, in `eureka.client.serviceUrl.defaultZone`{.literal}). The
price for using this option is an extra network round trip on startup,
to locate the service registration. The benefit is that, as long as the
Discovery Service is a fixed point, the Config Server can change its
coordinates. The default service ID is `configserver`{.literal}, but you
can change that on the client by setting
`spring.cloud.config.discovery.serviceId`{.literal} (and on the server,
in the usual way for a service, such as by setting
`spring.application.name`{.literal}).

The discovery client implementations all support some kind of metadata
map (for example, we have `eureka.instance.metadataMap`{.literal} for
Eureka). Some additional properties of the Config Server may need to be
configured in its service registration metadata so that clients can
connect correctly. If the Config Server is secured with HTTP Basic, you
can configure the credentials as `user`{.literal} and
`password`{.literal}. Also, if the Config Server has a context path, you
can set `configPath`{.literal}. For example, the following YAML file is
for a Config Server that is a Eureka client:

**bootstrap.yml. **

``` {.programlisting}
eureka:
  instance:
    ...
    metadataMap:
      user: osufhalskjrtl
      password: lviuhlszvaorhvlo5847
      configPath: /config
```

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#config-client-fail-fast)7.3 Config Client Fail Fast {.title style="clear: both"}
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

In some cases, you may want to fail startup of a service if it cannot
connect to the Config Server. If this is the desired behavior, set the
bootstrap configuration property
`spring.cloud.config.fail-fast=true`{.literal} to make the client halt
with an Exception.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#config-client-retry)7.4 Config Client Retry {.title style="clear: both"}
------------------------------------------------------------------------------------------------------------------------------------------------------------

If you expect that the config server may occasionally be unavailable
when your application starts, you can make it keep trying after a
failure. First, you need to set
`spring.cloud.config.fail-fast=true`{.literal}. Then you need to add
`spring-retry`{.literal} and `spring-boot-starter-aop`{.literal} to your
classpath. The default behavior is to retry six times with an initial
backoff interval of 1000ms and an exponential multiplier of 1.1 for
subsequent backoffs. You can configure these properties (and others) by
setting the `spring.cloud.config.retry.*`{.literal} configuration
properties.

![[Tip]](./Spring%20Cloud%20Config_files/tip.png)

Tip

To take full control of the retry behavior, add a `@Bean`{.literal} of
type `RetryOperationsInterceptor`{.literal} with an ID of
`configServerRetryInterceptor`{.literal}. Spring Retry has a
`RetryInterceptorBuilder`{.literal} that supports creating one.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_locating_remote_configuration_resources)7.5 Locating Remote Configuration Resources {.title style="clear: both"}
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The Config Service serves property sources from
`/{name}/{profile}/{label}`{.literal}, where the default bindings in the
client app are as follows:

-   "name" = `${spring.application.name}`{.literal}
-   "profile" = `${spring.profiles.active}`{.literal} (actually
    `Environment.getActiveProfiles()`{.literal})
-   "label" = "master"

![[Note]](./Spring%20Cloud%20Config_files/note.png)

Note

When setting the property `${spring.application.name}`{.literal} do not
prefix your app name with the reserved word `application-`{.literal} to
prevent issues resolving the correct property source.

You can override all of them by setting
`spring.cloud.config.*`{.literal} (where `*`{.literal} is
`name`{.literal}, `profile`{.literal} or `label`{.literal}). The
`label`{.literal} is useful for rolling back to previous versions of
configuration. With the default Config Server implementation, it can be
a git label, branch name, or commit ID. Label can also be provided as a
comma-separated list. In that case, the items in the list are tried one
by one until one succeeds. This behavior can be useful when working on a
feature branch. For instance, you might want to align the config label
with your branch but make it optional (in that case, use
`spring.cloud.config.label=myfeature,develop`{.literal}).

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_specifying_multiple_urls_for_the_config_server)7.6 Specifying Multiple Urls for the Config Server {.title style="clear: both"}
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

To ensure high availability when you have multiple instances of Config
Server deployed and expect one or more instances to be unavailable from
time to time, you can either specify multiple URLs (as a comma-separated
list under the `spring.cloud.config.uri`{.literal} property) or have all
your instances register in a Service Registry like Eureka ( if using
Discovery-First Bootstrap mode ). Note that doing so ensures high
availability only when the Config Server is not running (that is, when
the application has exited) or when a connection timeout has occurred.
For example, if the Config Server returns a 500 (Internal Server Error)
response or the Config Client receives a 401 from the Config Server (due
to bad credentials or other causes), the Config Client does not try to
fetch properties from other URLs. An error of that kind indicates a user
issue rather than an availability problem.

If you use HTTP basic security on your Config Server, it is currently
possible to support per-Config Server auth credentials only if you embed
the credentials in each URL you specify under the
`spring.cloud.config.uri`{.literal} property. If you use any other kind
of security mechanism, you cannot (currently) support per-Config Server
authentication and authorization.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_configuring_timeouts)7.7 Configuring Timeouts {.title style="clear: both"}
---------------------------------------------------------------------------------------------------------------------------------------------------------------

If you want to configure timeout thresholds:

-   Read timeouts can be configured by using the property
    `spring.cloud.config.request-read-timeout`{.literal}.
-   Connection timeouts can be configured by using the property
    `spring.cloud.config.request-connect-timeout`{.literal}.

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_security_2)7.8 Security {.title style="clear: both"}
-----------------------------------------------------------------------------------------------------------------------------------------

If you use HTTP Basic security on the server, clients need to know the
password (and username if it is not the default). You can specify the
username and password through the config server URI or via separate
username and password properties, as shown in the following example:

**bootstrap.yml. **

``` {.programlisting}
spring:
  cloud:
    config:
     uri: https://user:secret@myconfig.mycompany.com
```

The following example shows an alternate way to pass the same
information:

**bootstrap.yml. **

``` {.programlisting}
spring:
  cloud:
    config:
     uri: https://myconfig.mycompany.com
     username: user
     password: secret
```

The `spring.cloud.config.password`{.literal} and
`spring.cloud.config.username`{.literal} values override anything that
is provided in the URI.

If you deploy your apps on Cloud Foundry, the best way to provide the
password is through service credentials (such as in the URI, since it
does not need to be in a config file). The following example works
locally and for a user-provided service on Cloud Foundry named
`configserver`{.literal}:

**bootstrap.yml. **

``` {.programlisting}
spring:
  cloud:
    config:
     uri: ${vcap.services.configserver.credentials.uri:http://user:password@localhost:8888}
```

If you use another form of security, you might need to [provide a
`RestTemplate`{.literal}](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#custom-rest-template "7.8.2 Providing A Custom RestTemplate")
to the `ConfigServicePropertySourceLocator`{.literal} (for example, by
grabbing it in the bootstrap context and injecting it).

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_health_indicator_2)7.8.1 Health Indicator {.title}

The Config Client supplies a Spring Boot Health Indicator that attempts
to load configuration from the Config Server. The health indicator can
be disabled by setting `health.config.enabled=false`{.literal}. The
response is also cached for performance reasons. The default cache time
to live is 5 minutes. To change that value, set the
`health.config.time-to-live`{.literal} property (in milliseconds).

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#custom-rest-template)7.8.2 Providing A Custom RestTemplate {.title}

In some cases, you might need to customize the requests made to the
config server from the client. Typically, doing so involves passing
special `Authorization`{.literal} headers to authenticate requests to
the server. To provide a custom `RestTemplate`{.literal}:

1.  Create a new configuration bean with an implementation of
    `PropertySourceLocator`{.literal}, as shown in the following
    example:

**CustomConfigServiceBootstrapConfiguration.java. **

``` {.programlisting}
@Configuration
public class CustomConfigServiceBootstrapConfiguration {
    @Bean
    public ConfigServicePropertySourceLocator configServicePropertySourceLocator() {
        ConfigClientProperties clientProperties = configClientProperties();
       ConfigServicePropertySourceLocator configServicePropertySourceLocator =  new ConfigServicePropertySourceLocator(clientProperties);
        configServicePropertySourceLocator.setRestTemplate(customRestTemplate(clientProperties));
        return configServicePropertySourceLocator;
    }
}
```

1.  In `resources/META-INF`{.literal}, create a file called
    `spring.factories`{.literal} and specify your custom configuration,
    as shown in the following example:

**spring.factories. **

``` {.programlisting}
org.springframework.cloud.bootstrap.BootstrapConfiguration = com.my.config.client.CustomConfigServiceBootstrapConfiguration
```

### [](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_vault)7.8.3 Vault {.title}

When using Vault as a backend to your config server, the client needs to
supply a token for the server to retrieve values from Vault. This token
can be provided within the client by setting
`spring.cloud.config.token`{.literal} in `bootstrap.yml`{.literal}, as
shown in the following example:

**bootstrap.yml. **

``` {.programlisting}
spring:
  cloud:
    config:
      token: YourVaultToken
```

[](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.3.RELEASE/single/spring-cloud-config.html#_nested_keys_in_vault)7.9 Nested Keys In Vault {.title style="clear: both"}
---------------------------------------------------------------------------------------------------------------------------------------------------------------

Vault supports the ability to nest keys in a value stored in Vault, as
shown in the following example:

`echo -n '{"appA": {"secret": "appAsecret"}, "bar": "baz"}' | vault write secret/myapp -`{.literal}

This command writes a JSON object to your Vault. To access these values
in Spring, you would use the traditional dot(`.`{.literal}) annotation,
as shown in the following example

``` {.programlisting}
@Value("${appA.secret}")
String name = "World";
```

The preceding code would sets the value of the `name`{.literal} variable
to `appAsecret`{.literal}.
