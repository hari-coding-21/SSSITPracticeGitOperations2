<<<<<<< Updated upstream

story - 2

class preorder(BinaryNode node)
=======
story -1

class inorder(BinaryNode node)
>>>>>>> Stashed changes
{
    if(node == null)
    {
        return;
    }
<<<<<<< Updated upstream
    Sysout(node.value+" ");
    preorder(node.left);
    preorder(node.right);
=======
    inorder(node.left);
    Sysout(node.value+" ");
    inorder(node.right);
>>>>>>> Stashed changes
}
