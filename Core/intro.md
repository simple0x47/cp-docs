# Introduction

Core library for Cuplan's microservices.

## Installation

In order to be able to execute tests appropiately, the following environment variables must be defined within the test runner:

* `SECRETS_MANAGER_ACCESS_TOKEN`

You can define these environment variables within the following file: `Cuplan.sln.DotSettings.user`. Here's an example:

```
<wpf:ResourceDictionary xml:space="preserve" xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml" xmlns:s="clr-namespace:System;assembly=mscorlib" xmlns:ss="urn:shemas-jetbrains-com:settings-storage-xaml" xmlns:wpf="http://schemas.microsoft.com/winfx/2006/xaml/presentation">
	<s:String x:Key="/Default/Environment/UnitTesting/UnitTestSessionStore/Sessions/=c2ceb4bd_002D258c_002D4131_002Dab58_002D05334abf703b/@EntryIndexedValue">&lt;SessionState ContinuousTestingMode="0" IsActive="True" Name="BitwardenSecretsManagerTest" xmlns="urn:schemas-jetbrains-com:jetbrains-ut-session"&gt;
  &lt;TestAncestor&gt;
    &lt;TestId&gt;xUnit::34A6C6B7-D0DD-4FEB-A57F-2562BFE139D0::net8.0::Cuplan.Core.Tests.Secrets.BitwardenSecretsManagerTest&lt;/TestId&gt;
  &lt;/TestAncestor&gt;
&lt;/SessionState&gt;</s:String>
	<s:Boolean x:Key="/Default/Housekeeping/UnitTestingMru/UnitTestRunner/EnvironmentVariablesIndexed/=RESHARPER_005FHOST_005FVERSION/@EntryIndexRemoved">True</s:Boolean>
	<s:Boolean x:Key="/Default/Housekeeping/UnitTestingMru/UnitTestRunner/EnvironmentVariablesIndexed/=RESHARPER_005FHOST/@EntryIndexRemoved">True</s:Boolean>
	<s:String x:Key="/Default/Housekeeping/UnitTestingMru/UnitTestRunner/EnvironmentVariablesIndexed/=SECRETS_005FMANAGER_005FACCESS_005FTOKEN/@EntryIndexedValue">le_secret</s:String></wpf:ResourceDictionary>
```