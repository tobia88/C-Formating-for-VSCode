# C-Formating-for-VSCode
An json for auto formating omnisharp.json in new bracket style

Which represent the code style below:

function hello( int p1, int p2) {
  if( true ) {
    // this
  } else {
    // that
  }
}

Create new file name omnisharp.json locate at %USERPROFILE%/.omnisharp,
then paste the following codes to the file.

{
    "FormattingOptions": {
		"NewLine": "\n",
		"UseTabs": false,
		"TabSize": 4,
		"IndentationSize": 4,
		"SpacingAfterMethodDeclarationName": false,
		"SpaceWithinMethodDeclarationParenthesis": true,
		"SpaceBetweenEmptyMethodDeclarationParentheses": false,
		"SpaceAfterMethodCallName": false,
		"SpaceWithinMethodCallParentheses": true,
		"SpaceBetweenEmptyMethodCallParentheses": false,
		"SpaceAfterControlFlowStatementKeyword": false,
		"SpaceWithinExpressionParentheses": true,
		"SpaceWithinCastParentheses": true,
		"SpaceWithinOtherParentheses": true,
		"SpaceAfterCast": false,
		"SpacesIgnoreAroundVariableDeclaration": false,
		"SpaceBeforeOpenSquareBracket": false,
		"SpaceBetweenEmptySquareBrackets": false,
		"SpaceWithinSquareBrackets": false,
		"SpaceAfterColonInBaseTypeDeclaration": true,
		"SpaceAfterComma": true,
		"SpaceAfterDot": false,
		"SpaceAfterSemicolonsInForStatement": true,
		"SpaceBeforeColonInBaseTypeDeclaration": false,
		"SpaceBeforeComma": false,
		"SpaceBeforeDot": false,
		"SpaceBeforeSemicolonsInForStatement": false,
		"SpacingAroundBinaryOperator": "single",
		"IndentBraces": false,
		"IndentBlock": true,
		"IndentSwitchSection": true,
		"IndentSwitchCaseSection": true,
		"LabelPositioning": "oneLess",
		"WrappingPreserveSingleLine": true,
		"WrappingKeepStatementsOnSingleLine": true,
		"NewLinesForBracesInTypes": false,
		"NewLinesForBracesInMethods": false,
		"NewLinesForBracesInProperties": false,
		"NewLinesForBracesInAccessors": false,
		"NewLinesForBracesInAnonymousMethods": false,
		"NewLinesForBracesInControlBlocks": false,
		"NewLinesForBracesInAnonymousTypes": false,
		"NewLinesForBracesInObjectCollectionArrayInitializers": false,
		"NewLinesForBracesInLambdaExpressionBody": false,
		"NewLineForElse": false,
		"NewLineForCatch": false,
		"NewLineForFinally": false,
		"NewLineForMembersInObjectInit": false,
		"NewLineForMembersInAnonymousTypes": false,
		"NewLineForClausesInQuery": false
    }
}
 
