Eloqua SDK for .NET
=================
A software development kit for Eloqua that helps developers build applications that integrate with Eloqua.

## Usage

### Create Client
	var info = BulkClient.GetAccountInfo(Constants.Site, Constants.User, Constants.Passwd);
	var client = new BulkClient(Constants.Site, Constants.User, Constants.Passwd, Helpers.CurrentApiVersion(info));

### GET (list)
	List<ContactFilter> filters = _client.ContactFilters.Search("*", 1, 1);

## License
	Copyright [2012] [Fred Sakr]
	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at
	http://www.apache.org/licenses/LICENSE-2.0
	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.