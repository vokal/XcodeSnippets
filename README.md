# XcodeSnippets

> Maintained by [@bryanluby](https://github.com/bryanluby)

A repository of useful Swift and Objective-C Xcode snippets.

## Installation

- Clone this repo.
- Run the install script at the top-level of this repo: `./install.sh`
- This will copy all of the snippets into the user-level Xcode snippets directory.
- Restart Xcode if it is currently open to use the snippets.

## Adding Snippets

If you have any other Snippets that you would like to share make a Pull Request!

### Steps For Adding Snippets To This Repo

- Follow the directions [here](https://stackoverflow.com/questions/52417561/how-to-add-custom-code-snippets-in-xcode-10) for adding a snippet to Xcode.
- Then navigate to `~/Library/Developer/Xcode/UserData/CodeSnippets/` and find the `.codesnippet` file that was just created (sorting by Date Modified or Date Created helps).
- Drag that snippet file into the top-level of this repo folder and rename the file with either the `swift_` or `objc_` naming scheme similar to the other snippets.

## List of Snippets

### Swift

- `swift_mark`: `MARK: -` convenience snippet
- `swift_private_set_var`: `private(set) var ...` convenience snippet
- `swift_static_date_formatter`: Static date formatter snippet
- `swift_tableview_data_source`: Bare bones required `UITableViewDataSource` methods
- `swift_collectionview_data_source`: Bare bones required `UICollectionViewDataSource` methods

### Objective-C

- `objc_pragma_mark`: `#pragma mark - ...` snippet
- `objc_weakself`: `weakSelf` snippet
- `objc_strongSelf`: `strongSelf` snippet
- `objc_static_object_creation`: `static TYPE *const ...` snippet
- `objc_global_variable_interface`: `FOUNDATION_EXPORT TYPE *const ...` snippet for `.h` files
- `objc_global_variable_implementation`: `TYPE *const ...` snippet for `.m` files
- `objc_struct_types_interface`: Struct type for grouping constants for `.h` files
- `objc_struct_types_implementation`: Struct type for grouping constants for `.m` files
