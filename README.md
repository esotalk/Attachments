# Attachments Plugin

Allows users to attach files to their posts.

## Installation

[Download](https://github.com/esotalk/Attachments/archive/master.zip) or clone the Attachments plugin repo into your esoTalk plugin directory:

	cd ESOTALK_DIR/addons/plugins/
	git clone git@github.com:esotalk/Attachments.git Attachments

Navigate to the admin/plugins page and activate the Attachments plugin.

## Translation

Create `definitions.Attachments.php` in your language pack with the following definitions:

	$definitions["Attach a file"] = "Attach a file";
	$definitions["Drop files to upload"] = "Drop files to upload";
	$definitions["Embed in post"] = "Embed in post";
	$definitions["message.attachmentNotFound"] = "For some reason this attachment cannot be viewed. It may not exist, or you may not have permission to view it.";
	$definitions["Enter file extensions separated by a space. Leave blank to allow all file types."] = "Enter file extensions separated by a space. Leave blank to allow all file types.";
	$definitions["Allowed file types"] = "Allowed file types";
	
